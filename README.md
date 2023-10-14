# Memory Management

This repository contains the code for Assignment 6 of the Operating Systems Laboratory course, which focuses on implementing manual memory management for efficient coding.

## Assignment Description

- **Course**: Operating Systems Laboratory (CS39002)
- **Semester**: Spring Semester 2021-2022

### Assignment Overview

The assignment revolves around implementing a basic memory management module in C/C++ to demonstrate virtual memory management within an operating system. Key tasks include creating a custom memory management library, managing linked lists, and efficiently allocating and freeing memory.

### Key Features

1. **Memory Management Library**: Implemented as "goodmalloc.hpp" and "goodmalloc.cpp," the library provides various functionalities for memory management, including creating memory segments, managing linked lists, and assigning values to list elements.

2. **Custom Data Structures**: The library employs custom data structures for memory allocation and linked list management.

3. **Paging and Page Tables**: Concepts learned in paging and page tables are used to implement memory allocation strategies, such as First Fit or Best Fit.

4. **Demo Code (mergesort.cpp)**: The repository includes a "mergesort.cpp" code that demonstrates the library's functionality. It allocates 250 MB of memory, creates a linked list of 50,000 elements, fills them with random integers, and performs a recursive merge sort.

### Report

The repository also contains a report ("report.pdf") that describes the design decisions made in the code. It covers the structure of the internal page table, additional data structures/functions used in the library, and the impact of the `freeElem()` function on merge sort performance.

### Compilation and Execution

- Use the provided "Makefile" to compile and run the "mergesort.cpp" code.

## Repository Structure

- **goodmalloc.hpp**: Header file for the memory management library.
- **goodmalloc.cpp**: Implementation file for the memory management library.
- **mergesort.cpp**: Main code demonstrating the library's functionality.
- **Makefile**: Used for compiling and running the mergesort code.
- **report.pdf**: Report describing design decisions and performance analysis.

## How to Use

1. Clone the repository to your local machine.
2. Use the Makefile to compile and run the "mergesort.cpp" code.
3. Refer to the "Report.pdf" for detailed insights into the design decisions and performance analysis.

## Contributing

Feel free to contribute to this project by opening issues, suggesting improvements, or submitting pull requests.