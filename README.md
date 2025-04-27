# Monkey Programming Language Interpreter

This project is an implementation of the Monkey programming language interpreter from the book "Writing an Interpreter in Go" by Thorsten Ball.

## Overview

The Monkey programming language is a small, dynamically-typed language with C-like syntax that supports:

- Variable bindings
- First-class and higher-order functions
- Closures
- Integer and boolean data types
- Built-in functions
- Arrays and hash maps

This implementation follows the book chapter by chapter, building the interpreter from scratch in Go.

## Project Structure

```
writing-an-interpreter-in-go/
├── lexer/         # Lexer implementation - transforms source code into tokens
│   ├── lexer.go
│   └── lexer_test.go
├── token/         # Token definitions and types
│   └── token.go
└── go.mod         # Go module definition file
```

## Current Progress

- [x] Chapter 1: Lexing - Basic token definition and lexer implementation
- [ ] Chapter 2: Parsing
- [ ] Chapter 3: Evaluation
- [ ] Chapter 4: Extending the Interpreter

## Running Tests

To run the tests for the lexer:

```bash
go test ./lexer
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project is based on the book "Writing an Interpreter in Go" by Thorsten Ball.

- [Book Website](https://interpreterbook.com/)
- [Original Source Code](https://github.com/thorstenball/monkey)
