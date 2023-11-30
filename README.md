# LALR-Parser-Using-GUI

This repository contains a Look-Ahead LR (LALR) parser implemented using Python Lex-Yacc (PLY) library. The parser is designed to evaluate arithmetic expressions and includes a graphical user interface (GUI) created with Tkinter.

## Overview

The project consists of two main components:

- **Lexer (`ply.lex`)**: The lexer tokenizes the input into fundamental elements like numbers and arithmetic operators.
- **Parser (`ply.yacc`)**: The parser evaluates the structure of the tokenized input and computes the result based on the defined grammar rules.

Additionally, a GUI is integrated for easy interaction with the parser.

## Features

- Supports basic arithmetic operations: addition, subtraction, multiplication, division, and exponentiation.
- Handles parentheses to alter the standard precedence of operations.
- Provides error feedback for syntax errors and illegal characters.
- Graphical interface for user-friendly interaction.

## Files

- `ply.lex`: Contains the lexer implementation and token definitions.
- `ply.yacc`: Contains the parser implementation and grammar rules.
- `parser.out`: A generated file by PLY that details the states and transitions of the parser based on the defined grammar.
- `GUI Implementation`: A Tkinter-based interface for interacting with the parser.

## Usage

To use the parser, run the Tkinter application. Enter an arithmetic expression in the provided input field and click "Calculate" to evaluate the expression. The result or any error messages will be displayed on the interface.

## Requirements

- Python 3.x
- PLY (Python Lex-Yacc)
- Tkinter (usually comes pre-installed with Python)
