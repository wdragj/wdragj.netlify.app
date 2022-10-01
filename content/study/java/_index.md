---
title: Java
linkTitle: Java
summary: Organized study material on Java programming language.
date: '2021-01-24'
type: book
tags:
  - Java
---

{{< figure src="featured.png" >}}

{{< toc hide_on="xl" >}}

## About java
---
- **Java is a simple programming language**:
  - Java is based on C++
  - Java has removed many confusing and rarely-used features e.g. explicit pointers, operator overloading, etc
  - Java takes care of memory management and
  - Java provides an automatic garbage collector. This collects the unused objects automatically.
- **Java is a platform-independent language:**
  - The programs written in Java language, after compilation, are converted into an intermediate level language called the bytecode
  - Bytecode is a part of the Java platform irrespective of the machine on which the programs run
  - This makes java highly portable as its bytecodes can be run on any machine by an interpreter called the Java Virtual Machine(JVM)
  - Therefore, java provides ‘reusability of code’.
- **Java is an object-oriented programming language:**
  - OOP makes the complete program simpler by dividing it into a number of objects
  - The objects can be used as a bridge to have data flow from one function to another
  - We can easily modify data and function’s as per the requirements of the program
- **Java is a robust language:**
  - Java programs must be reliable because they are used in both consumer and mission-critical applications, ranging from Blu-ray players to navigation systems
- **Java is a multithreaded language:**
  - Java can perform many tasks at once by defining multiple threads
  - For example, a program that manages a Graphical User Interface (GUI) while waiting for input from a network connection uses another thread to perform and wait’s instead of using the default GUI thread for both tasks
  - This keeps the GUI responsive
- **Java programs can create applets:**
  - Applets are programs that run in web browsers
  - But applets support was deprecated in Java 9 release and has been removed in Java 11 release due to waning browser support for the Java plugin
- **Java does not require any preprocessor:**
  - Java does not require inclusion of header files for creating a Java application

<br/><br/>

## Java Terminology
---
Below are some common terms of Java.  
1. **Java Virtual Machine(JVM):**
   * This is generally referred to as JVM
   * There are **three** execution phases of a program
   * They are written, compile and run the program

<br/><br/>

## Courses in this program
---
{{< list_children >}}