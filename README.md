# ALX Monty Project

## Description
This project is a collaborative effort between Anthony Gidambayi (gidambayiantony@gmail.com) and Mary G (mariwamuyu@gmail.com) to develop a Monty interpreter. The Monty interpreter is designed to read and execute Monty bytecode files (.m) containing opcodes that perform various operations.

## Project Files
The project files in this repository include:

- `add.c`: File containing logic for addition operation.
- `div.c`: File containing logic for division operation.
- `free_stack.c`: File with logic to free the stack memory.
- `mod.c`: File containing logic for modulo operation.
- `monty.h`: Header file with function prototypes and structures.
- `nop.c`: File containing logic for the 'nop' operation.
- `pchar.c`: File with logic for printing the character at the top of the stack.
- `pop.c`: File with logic to remove the top element of the stack.
- `push.c`: File with logic to push an element onto the stack.
- `README.md`: This file, describing the project and its contents.
- `rotr.c`: File containing logic to rotate the stack to the right.
- `sub.c`: File containing logic for subtraction operation.
- Other files: Additional files for various operations and main execution logic.

## Usage
To compile the Monty interpreter, navigate to the project directory and run the following command:

```bash
gcc -Wall -Werror -Wextra -pedantic *.c -o monty

To execute Monty bytecode files, use the compiled monty executable followed by the bytecode file. For example:

./monty file.m

## Contributors
- Anthony Gidambayi - [gidambayiantony@gmail.com](mailto:gidambayiantony@gmail.com)
- Mary G - [mariwamuyu@gmail.com](mailto:mariwamuyu@gmail.com)

