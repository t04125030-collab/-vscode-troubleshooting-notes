# C Language Setup in VS Code

## Overview

Visual Studio Code is a code editor. To compile and run C programs, you also need a C compiler.

## Requirements

- Visual Studio Code
- A C compiler, such as GCC
- The C/C++ extension for VS Code

## Basic Setup

1. Install a suitable C compiler for your operating system.
2. Install the C/C++ extension in VS Code.
3. Configure the compiler and PATH if required.
4. Create a file named `main.c`.
5. Write your C program and save it.
6. Compile and run it using your installed compiler.

## Example Program

```c
#include <stdio.h>

int main(void)
{
    printf("Hello, World!\n");
    return 0;
}
```

## Common Problems

- GCC is not recognized: Check the compiler installation and PATH.
- Compiler not found: Verify that the compiler is installed correctly.
- Program fails to compile: Read the compiler error message and correct the code.

---

*Practical notes for C programming beginners.*You can take notes for Code With Harry YT Channel and from Greeks from Greeks, and you can also cretae your own notes by
own .
When You found an error like gcc not recognized or any other comiler like compiler are not recognized,first of all you should add the compiler in path,
and then check the debugger is off in the code editor ,
