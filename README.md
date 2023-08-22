#0x19. C - Stacks, Queues - LIFO, FIFO

# Monty Bytecode Interpreter

The Monty Bytecode Interpreter is a program that reads and executes Monty byte code files. Monty is a scripting language that relies on a unique stack with specific instructions to manipulate it. This project implements the interpreter in C and provides functionality for executing Monty byte code files.

## Table of Contents

- [Overview](#overview)
- [Building](#building)
- [Supported Opcodes](#supported-opcodes)
- [File Structure](#file-structure)
- [Advanced Tasks](#advanced-tasks)
- [Contributing](#contributing)

## Overview

The Monty Bytecode Interpreter reads Monty byte code files (usually with the .m extension) and executes the specified instructions using a stack data structure. The interpreter supports various opcodes that allow you to push, pop, print, swap, and perform other operations on the stack.

# Building
To build the Monty interpreter, you can use the provided compilation command. Open a terminal in the project directory and run the following command:
gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty

# Supported Opcodes
The Monty interpreter supports various opcodes, including:

1. push: Pushes an integer onto the stack.
2. pall: Prints all the values on the stack.
3. pint: Prints the value at the top of the stack.
4. pop: Removes the top element from the stack.
5. swap: Swaps the top two elements on the stack.
6. add: Adds the top two elements on the stack.
7. nop: No operation.
... (and others)

# File Structure
1. monty.h: Header file containing data structures and opcode function prototypes.
2. push.c, pint.c, swap.c, pop.c, ...: Opcode implementations for various opcodes.
3. main.c: Main program logic for reading and executing Monty byte code files.

# Advanced Tasks
The Monty Bytecode Interpreter also supports advanced tasks, such as:

1. sub: Subtract top element from the second top element.
2. div: Divide the second top element by the top element.
3. mul: Multiply the second top element with the top element.
mod: Calculate the rest of division of the second top element by the top element.
... (and others)

# Contributing
Only Idah Khumalo Who craeted the project is allowed to make contributions to the project.
