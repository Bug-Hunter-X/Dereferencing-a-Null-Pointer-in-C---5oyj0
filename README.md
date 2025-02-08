# Dereferencing a Null Pointer in C++

This repository demonstrates a common C++ error: dereferencing a null pointer.  Dereferencing a null pointer (attempting to access the memory location pointed to by a null pointer) leads to undefined behavior, typically resulting in a segmentation fault or program crash.

The `bug.cpp` file contains the erroneous code. The `bugSolution.cpp` file provides a corrected version.

## How to Reproduce

1. Compile the `bug.cpp` file using a C++ compiler (like g++).
2. Run the compiled executable.  You should observe a segmentation fault or similar error.

## Solution

The solution involves carefully checking for null pointers before dereferencing them.  Always ensure that a pointer is valid before accessing the memory it points to.