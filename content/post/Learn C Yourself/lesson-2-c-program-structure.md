+++
authors = []
date = 2015-06-01T18:00:00Z
excerpt = "A C program basically consists of the following parts. Preprocessor Commands, Functions, Variables, Statements & Expressions, Comments"
hero = "/images/c-language.jpg"
timeToRead = 2
title = "Lesson 2: C – Program Structure"

+++
**C Hello World Example**

**Before we study basic building blocks of the C programming language, let us look at a bare minimum C program structure so that we can take it as a reference in upcoming chapters.**

A C program basically consists of the following parts:

* Preprocessor Commands
* Functions
* Variables
* Statements & Expressions
* Comments

Let us look at a simple code that would print the words “Hello World!”:

# Let us look at various parts of the above program

1. The first line of the program #include <stdio.h> is a preprocessor command, which tells a C compiler to include stdio.h file before going to actual compilation.
2. The next line int main() is the main function where program execution begins.
3. The next line /* my first program in C*/ will be ignored by the compiler and it has been put to add additional comments in the program. So such lines are called comments in the program.
4. The next line printf(“Hello World!”) is another function available in C which causes the message **“Hello World!”** to be displayed on the screen.
5. The next line return 0 terminates **main()** function and returns the value 0.

# Compile & Execute C Program

Let’s look at how to save the source code in a file, how to compile and run it. Following are the simple steps:

1. Open your C/C++ compiler and add the above-mentioned code.
2. Save the file as Hello World.c
3. Now Compile and run by clicking F9 (Code::Blocks).
4. If there are no errors in your code the compiler will create a window that will display **"Hello World!"**.

For more information contact [Facebook](http://www.facebook.com/sakibsadmanshajib) or [Gmail](mailto:sakibsadmanshajib@gmail.com) or [Youtube](https://goo.gl/vCiz6f)