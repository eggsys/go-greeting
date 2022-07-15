In Go, the := operator is a shortcut for declaring and initializing a variable in one line (Go uses the value on the right to determine the variable's type). Taking the long way, you might have written this as:

```go
var message string
message = fmt.Sprintf("Hi, %v. Welcome!", name)
```

- Use the fmt package's Sprintf function to create a greeting message. The first argument is a format string, and Sprintf substitutes the name parameter's value for the %v format verb. Inserting the value of the name parameter completes the greeting text.

- Return the formatted greeting text to the caller.