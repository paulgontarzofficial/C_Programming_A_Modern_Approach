# Chapter 02 -- \[C Fundamentals\]

Date Studied: 16FEB26
Time Spent:

------------------------------------------------------------------------

## 🎯 Chapter Objectives

-	Learning how to compile and link a C program. 
-	Learn how to Generalize the program.
-	Learn how to add explanatory remarks such as comments within the code.
-	Introduction to variables
-	Learning how to use the scanf function to read data into variables. 
-	Constants and what they are.
-   C's rules for creating names (identifiers). 
-   Rules for laying out the program. 

------------------------------------------------------------------------

## 🧠 Key Concepts

### 1. Writing a Simple Program 

**Definition:**\
Printing a pun to the terminal is just like writing "Hello World!" to the terminal 
however we are just using a different string literal to print. Instead of 
"Hello World!" we are going to use the pun "To C, or not to C: that is the question". 

**Why It Matters:**\
This concept gets us going writing code and having the computer do something. 

**Syntax Example:**

``` c
#include <stdio.h>

int main(void) {
	printf("To C, or not to C: that is the question.\n");
	return 0;
}
```

## **Important Notes:**

-   
-   

--------------------------------------------------------------------------

### 2. Compiling and Linking 

**Definition:**\
Compiling and Linking refers to the process of getting the code to run on the machine. 

**Why It Matters:**\
If we can't compile and link our code that we have developed then we can't even run our 
code to begin with. All that time... WASTED!

**Conversion Process**
1. Preprocessing: The program is first given to a preprocessor, which obeys commands that begin with # (known as a directive).
A preprocessor is sort of like a text editor; it can add things to the program and make modifications.
2. Compiling: The modified program now goes to a compiler, which translates the code into machine instructions (object code). 
3. Linking: The final step combines the object code producedby the compiler with any additional code needed to yield a
complete executable program. This additional code includes library functions (like printf) that are used in the program. 

## **Important Notes:**

-	We are going to be using gcc as our compiler for the duration of this textbook.   
-   

------------------------------------------------------------------------

-----------------------------------------------------------------------

### 3. General Form of Simple Programs 

**Definition:**\
This sets us with a solid foundation on how a simple program may look in C. 

**Directives**
Reminder, directives are commands that are intended for the preprocessor. An example of a directive would be
`#include <stdio.h>` the `#include` is the text that is considered the directive. The `<stdio.h>` is the header
file that we must include because C does not have any built-in "read" and "write" commands. 

**Syntax Example:**

``` c
directives

int main(void) {
	statements
}
```

## **Important Notes:**

-	   
-   

------------------------------------------------------------------------

-----------------------------------------------------------------------

### 4. Concept Name

**Definition:**\

**Why It Matters:**\

**Syntax Example:**

``` c

```

## **Important Notes:**

-   
-   

------------------------------------------------------------------------

## 🔎 Under the Hood

-   What happens in memory?
-   Stack vs Heap implications?
-   Compiler behavior?
-   Any undefined behavior risks?

------------------------------------------------------------------------

## ⚠️ Common Mistakes / Pitfalls

-   
-   
-   

------------------------------------------------------------------------

## 🧪 Experiments

### Experiment Title

**Goal:**

**Code:**

``` c
```

**Result:**

**What I Learned:**

------------------------------------------------------------------------

## 📌 Exercise Notes

### Exercise X

**Problem Summary:**

**Approach:**

**Final Code:**

``` c
```

**Improvements:**

------------------------------------------------------------------------

## 🛠 Debugging & Compilation Notes

Commands Used:

``` bash
gcc -Wall -Wextra -Werror -std=c11 file.c
gdb ./a.out
```

## Observations:

-   

------------------------------------------------------------------------

## 🔁 Review Checklist

-   Can I explain all major concepts without notes?
-   Can I implement examples from memory?
-   Do I understand memory implications?
-   What needs more practice?

------------------------------------------------------------------------

## 📚 Additional Research (Optional)

-   `man` pages reviewed:
-   Related POSIX behavior:
-   Assembly observations:
-   Real-world usage examples:

------------------------------------------------------------------------
