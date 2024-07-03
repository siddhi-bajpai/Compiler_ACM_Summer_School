# COMPILER

This project is a compiler that converts AIDSL (Artificial Intelligence Domain-Specific Language) into C++ code. Developed using Lex and Yacc tools with C++ and C, it includes:

- **Variable Declarations**: Supports `int32` and `int8` types for scalars and tensors.
- **Assignments and Expressions**: Parses arithmetic expressions and assignments.
- **Symbol Table Management**: Manages variable declarations with insertion and lookup functionalities.
- **Type Checking**: Ensures correct type usage in expressions and assignments.
- **Code Generation**: Generates corresponding C++ code for scalar and tensor operations.

The compiler processes AIDSL syntax and translates it into C++ code, facilitating the execution of AIDSL programs.
