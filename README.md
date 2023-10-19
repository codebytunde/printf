# ALX Africa printf Project

## Introduction

This is a description of my journey through the ALX Africa printf project, where I've been tasked with creating a simplified version of the `printf` function in the C programming language.

## Project Overview

The `printf` function is a fundamental and powerful tool in C that allows us to format and display text and data. Our task is to implement a simplified version of this function, adhering to certain requirements and constraints.

### Project Requirements

- Create a function named `_printf` with the following prototype:
  ```c
  int _printf(const char *format, ...);
  ```
- The function should return the number of characters printed (excluding the null byte used to end output to strings).
- Output should be written to `stdout`, the standard output stream.
- The `format` is a character string composed of directives, similar to the `printf` function.
- We must handle the conversion specifiers for the following:
  - `%c`: Character
  - `%s`: String
  - `%%`: Literal `%`
- We do not need to handle:
  - Flag characters
  - Field width
  - Precision
  - Length modifiers

## Development Process

### Understanding the Requirements

Before diving into coding, I spent time understanding the project requirements and constraints. This included reading the provided project description and reviewing the expectations for the `_printf` function.

### Coding and Implementation

I started by creating a structure for the project. I organized my code into separate functions and files, adhering to the guidelines provided by ALX Africa. I implemented the core functionality for handling character, string, and literal '%' conversions.

### Testing and Debugging

I wrote test cases to ensure that the `_printf` function was working correctly. I tested various scenarios, including different combinations of conversion specifiers, and checked for edge cases. Debugging was an essential part of this phase to fix any issues that arose during testing.

### Documentation and Style

I followed the Betty coding style guide to ensure that my code was well-formatted and easy to read. Proper documentation, including comments and a `README.md` file, was crucial to provide clear instructions and explanations.

## Conclusion

The ALX Africa printf project challenged me to apply my C programming skills to create a fundamental utility. Through a structured development process and rigorous testing, I successfully implemented the `_printf` function, adhering to the given requirements and constraints.

This project allowed me to strengthen my understanding of C programming and improve my problem-solving skills. It was a valuable learning experience, and I'm proud of the outcome.
