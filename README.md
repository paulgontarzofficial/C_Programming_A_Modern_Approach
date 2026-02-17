# C: A Modern Approach -- Workspace

This repository serves as a structured workspace for studying and
practicing concepts from:

**C: A Modern Approach (2nd Edition) by K. N. King**

The purpose of this repository is to reinforce foundational C
programming skills through structured exercises, experiments, notes, and
deeper exploration of systems-level concepts.

------------------------------------------------------------------------

## 📌 Objectives

-   Build strong fundamentals in C programming
-   Develop comfort with memory management and pointers
-   Understand how C interacts with the underlying system
-   Write clean, portable, standards-compliant C code
-   Prepare for systems programming, reverse engineering, and low-level
    development

------------------------------------------------------------------------

## 🗂 Repository Structure

    c-modern-approach/
    │
    ├── chapter-01/
    │   ├── notes.md
    │   ├── exercises/
    │   └── projects/
    │
    ├── chapter-02/
    │   ├── notes.md
    │   ├── exercises/
    │   └── projects/
    │
    ├── common/
    │   ├── templates/
    │   ├── headers/
    │   └── utilities/
    │
    ├── build/
    │
    ├── Makefile
    └── README.md

### Structure Breakdown

-   **chapter-XX/**\
    Contains all work related to a specific chapter:

    -   `notes.md` → Key concepts summarized
    -   `exercises/` → End-of-chapter exercises
    -   `projects/` → Larger programming assignments

-   **common/**\
    Shared utilities, reusable headers, and templates.

-   **build/**\
    Compiled binaries (excluded via `.gitignore`).

------------------------------------------------------------------------

## 🛠 Build Instructions

Using GCC:

``` bash
gcc -Wall -Wextra -Werror -std=c11 program.c -o program
```

Using Make:

``` bash
make
```

Clean build files:

``` bash
make clean
```

------------------------------------------------------------------------

## 🧠 Learning Approach

For each chapter:

1.  Read the chapter thoroughly.
2.  Summarize key concepts in `notes.md`.
3.  Complete all programming exercises.
4.  Rewrite challenging problems from memory.
5.  Refactor code for clarity and standards compliance.
6.  Add additional experiments to deepen understanding.

------------------------------------------------------------------------

## 🔍 Focus Areas

-   Data types and operators
-   Control flow
-   Functions and modularity
-   Arrays and pointers
-   Strings and memory
-   Structures and unions
-   Dynamic memory allocation
-   File I/O
-   Preprocessor directives

------------------------------------------------------------------------

## 📚 Compilation Standards

All code in this repository follows:

-   C11 standard (`-std=c11`)
-   Strict compiler warnings enabled
-   Clear naming conventions
-   Modular design where appropriate
-   Minimal global state

------------------------------------------------------------------------

## 🎯 Long-Term Goals

-   Master manual memory management
-   Write efficient and predictable C programs
-   Build intuition for stack vs heap behavior
-   Prepare for:
    -   Systems programming
    -   Reverse engineering
    -   Exploit development
    -   Operating systems concepts

------------------------------------------------------------------------

## 🚀 Future Enhancements

-   Add debugging examples using `gdb`
-   Add memory analysis with `valgrind`
-   Include benchmarking experiments
-   Port selected exercises to POSIX environments
-   Compare implementations against assembly output

------------------------------------------------------------------------

## 🧩 Recommended Companion Tools

-   `gcc`
-   `clang`
-   `gdb`
-   `valgrind`
-   `make`
-   `man` pages

------------------------------------------------------------------------

## 📎 Notes

This repository is strictly for educational purposes and personal skill
development.\
All credit for instructional content belongs to the original author.
