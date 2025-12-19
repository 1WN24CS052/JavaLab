# Java Object Oriented Programming – Lab Programs

## Student Details

* *Name:* ASAM SAI NISHITH REDDY
* *USN:* 1WN24CS052
* *Class:* 3R

---

## Repository Description

This repository contains *eight Java programs* developed as part of the *Object Oriented Programming using Java* laboratory syllabus.
Each program demonstrates core Java concepts such as *classes and objects, inheritance, polymorphism, abstraction, exception handling, multithreading, packages, and interfaces*.

All programs are written following standard Java conventions and are suitable for *lab examinations, viva preparation, and academic reference*.

---

## List of Programs

---

### *Program 1: Quadratic Equation Solver*

*Question:*
Develop a Java program that prints all real solutions to the quadratic equation
ax² + bx + c = 0.
Read in a, b, c and use the quadratic formula. If the discriminant
b² − 4ac is negative, display a message stating that there are no real solutions.

*Concepts Used:*

* Conditional statements
* Mathematical computation
* Input handling

---

### *Program 2: Student SGPA Calculator*

*Question:*
Develop a Java program to create a class Student with members usn, name, an array credits, and an array marks.
Include methods to accept and display details and a method to calculate the *SGPA* of a student.

*Concepts Used:*

* Classes and objects
* Arrays
* Methods
* Encapsulation

---

### *Program 3: Book Class with toString()*

*Question:*
Create a class Book which contains four members: name, author, price, num_pages.
Include a constructor to set values, getter and setter methods, and override the toString() method to display complete book details.
Develop a Java program to create n book objects.

*Concepts Used:*

* Constructors
* Encapsulation
* Method overriding
* toString() method

---

### *Program 4: Abstract Shape Class*

*Question:*
Develop a Java program to create an abstract class named Shape that contains two integers and an abstract method printArea().
Provide classes Rectangle, Triangle, and Circle that extend Shape and implement printArea() to compute the area of respective shapes.

*Concepts Used:*

* Abstract classes
* Inheritance
* Runtime polymorphism

---

### *Program 5: Bank Account System*

*Question:*
Develop a Java program to create a class Bank that maintains two types of accounts:

* *Savings Account* (interest + withdrawal, no cheque book)
* *Current Account* (cheque book, minimum balance, penalty if violated)

Create a base class Account and derive SavAcct and CurAcct.
Implement methods for deposit, withdrawal, interest computation, and balance display.

*Concepts Used:*

* Inheritance
* Method overriding
* Real-world modeling
* Conditional logic

---

### *Program 6: Packages – CIE and SEE*

*Question:*
Create a package CIE containing classes Personal and Internals.
Create another package SEE containing class External derived from Personal.
Write a program to import both packages and compute final marks of n students in five subjects.

*Concepts Used:*

* Packages
* Access specifiers
* Inheritance across packages
* Arrays

---

### *Program 7: Exception Handling in Inheritance*

*Question:*
Write a program to demonstrate exception handling in an inheritance hierarchy.
Create a base class Father and derived class Son.
Throw a custom exception WrongAgeException if:

* Father’s age is negative
* Son’s age is greater than or equal to father’s age

*Concepts Used:*

* Custom exceptions
* Exception handling
* Inheritance
* Constructors throwing exceptions

---

### *Program 8: Multithreading*

*Question:*
Write a Java program to create two threads:

* One thread displays *“BMS College of Engineering”* once every 10 seconds
* Another thread displays *“CSE”* once every 2 seconds

*Concepts Used:*

* Multithreading
* Runnable interface
* Thread.sleep()
* Concurrent execution

---

## How to Run the Programs

1. Ensure *Java JDK* is installed.
2. Compile the program using:

   bash
   javac FileName.java
   
3. Run the program using:

   bash
   java FileName
   
4. For package-based programs, ensure proper directory structure is maintained.

---

## Academic Use

This repository is intended for:

* Java OOPS laboratory practice
* Viva and practical exam preparation
* Reference for object-oriented design in Java

---

## Declaration

All programs in this repository are written and compiled by *Anish Balabattuni* as part of academic coursework and follow standard Java programming practices.

---
