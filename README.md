# Java Programming Portfolio

> A collection of practical Java programming exercises completed throughout the **BIT1123 Object-Oriented Programming** course at **City University Malaysia**. This repository demonstrates my progress in learning Java programming, Object-Oriented Programming (OOP), and software development fundamentals through weekly practical tutorials.

<p align="left">

![Java](https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=openjdk)
![Course](https://img.shields.io/badge/Course-BIT1123-blue?style=for-the-badge)
![OOP](https://img.shields.io/badge/Object%20Oriented%20Programming-Java-success?style=for-the-badge)


</p>

---

# Student Information

| Item | Details |
|------|---------|
| **Student Name** | Bandar Khaled Salem Bawazir |
| **Student ID** | 202401010116 |
| **Course** | BIT1123 – Object-Oriented Programming |
| **University** | City University Malaysia |
| **Programming Language** | Java |
| **IDE** | Visual Studio Code |
| **Version Control** | Git & GitHub |

---

# About

This repository contains all practical tutorials completed during the **BIT1123 Object-Oriented Programming** course.

Throughout the semester, I progressively developed my understanding of Java programming, beginning with basic syntax and gradually advancing to Object-Oriented Programming concepts including encapsulation, inheritance, polymorphism, abstraction, collections, file handling, and graphical user interface (GUI) development using Java Swing.

Each folder represents the work completed during a specific tutorial, highlighting the knowledge and practical programming skills gained throughout the course.

---

# Repository Structure

```text
Java Programming Portfolio
│
├── week_01
├── week_02
├── week_03_04
├── week_05
├── week_06
├── week_07
├── week_08_09
├── week_10
│
└── README.md
```

---

# Weekly Tutorials

## Week 01 : Hello World

### Objective

Develop the first Java application to understand the structure of a Java program and become familiar with compiling and executing Java applications.

### Source Files

- HelloWorld.java

### Topics Covered

- Java Program Structure
- Class Declaration
- main() Method
- Console Output
- System.out.println()

### Summary

This tutorial introduces the Java programming language through the implementation of the classic **Hello World** application. It establishes the foundation for understanding Java syntax, program execution, and the structure of every Java application.

### Expected Output

```text
Hello World!
```

---

## Week 02 : Classes and Objects

### Objective

Create a Student class to understand the fundamentals of object-oriented programming, including objects, attributes, constructors, and methods.

### Source Files

- Student.java
- Main.java

### Topics Covered

- Classes
- Objects
- Constructors
- Attributes
- Methods
- Access Modifiers

### Summary

A Student class was developed containing attributes such as name, age, and GPA. Constructors were used to initialize object data, while methods were implemented to display student information and simulate student activities. This tutorial introduced the basic principles of object-oriented design and object creation.

### Expected Output

```text
Name: Ali
Age: 20
GPA: 3.75
Ali is studying.
Ali is taking an exam.
```

---

## Week 03 & Week 04 : Inheritance and Polymorphism

### Objective

Apply inheritance and polymorphism by creating a class hierarchy consisting of Person, Student, and Lecturer.

### Source Files

- Person.java
- Student.java
- Lecturer.java
- Main.java

### Topics Covered

- Inheritance
- Polymorphism
- Method Overriding
- Superclass
- Subclass

### Summary

This tutorial demonstrates inheritance by extending the Person class into Student and Lecturer subclasses. Each subclass overrides the `introduce()` method to provide its own implementation, illustrating runtime polymorphism and object-oriented programming principles.

### Expected Output

```text
I am a person.
I am a student.
I am a lecturer.
```

---

## Week 05 : Encapsulation

### Objective

Understand encapsulation by protecting object data using private variables together with getter and setter methods.

### Source Files

- Student.java
- Main.java
- documentation.txt

### Topics Covered

- Encapsulation
- Private Variables
- Getter Methods
- Setter Methods
- Data Hiding

### Summary

A Student Information System was implemented using private instance variables and public getter and setter methods. This tutorial demonstrates how encapsulation protects object data while allowing controlled access through dedicated methods. A short documentation file was also prepared to explain the importance of private variables, getters, and setters in object-oriented programming.

### Expected Output

```text
Student ID : CU12345
Name       : Ali
CGPA       : 3.75
Programme  : BIT
```

---

## Week 06 : Inheritance

### Objective

Apply inheritance by extending an existing class and promoting code reusability through parent-child relationships.

### Source Files

- Employee.java
- Lecturer.java
- Main.java

### Topics Covered

- Inheritance
- Constructor Chaining
- super Keyword
- Protected Variables
- Code Reusability

### Summary

This tutorial demonstrates inheritance by creating an `Employee` base class and extending it with a `Lecturer` subclass. The subclass inherits common employee information while introducing additional attributes such as subject and department. Constructor chaining using the `super` keyword is also demonstrated.

### Expected Output

```text
Employee ID : L100
Name        : Dr Ahmad
Subject     : Java Programming
Department  : Faculty of Information Technology
```

---

## Week 07 : Abstract Classes

### Objective

Explore abstraction by implementing abstract classes and abstract methods in Java.

### Source Files

- Appliance.java
- AirConditioner.java
- Refrigerator.java
- WashingMachine.java
- Main.java

### Topics Covered

- Abstract Classes
- Abstract Methods
- Method Overriding
- Inheritance
- Runtime Polymorphism

### Summary

An abstract `Appliance` class was created to define common functionality shared by multiple household appliances. Each subclass provides its own implementation of the abstract `operate()` method, demonstrating abstraction while maintaining code flexibility and reusability.

### Expected Output

```text
Brand : LG
Power ON
Washing clothes...
Power OFF

Brand : Panasonic
Power ON
Store food & beverages...
Power OFF
```

---

## Week 08 & Week 09 : Collections and File Handling

### Objective

Develop a simple task management application using Java Collections and File Handling.

### Source Files

- Main.java

### Topics Covered

- ArrayList
- User Input
- Loops
- BufferedReader
- BufferedWriter
- FileReader
- FileWriter
- Exception Handling

### Summary

A console-based task management system was developed using an `ArrayList` to store user tasks. The application allows users to enter tasks, save them into a text file, and load them again from the file. This tutorial demonstrates the practical use of Java collections together with file input and output operations.

### Expected Output

```text
===== ADD TASKS =====

Enter Task 1: Go to university
Enter Task 2: Study
Enter Task 3: Sleep

===== TASK LIST =====

1. Go to university
2. Study
3. Sleep

Tasks saved successfully.

===== TASKS LOADED FROM FILE =====

Go to university
Study
Sleep
```

---

## Week 10 : Programming Quiz Battle

### Objective

Develop an interactive desktop application using Java Swing to demonstrate graphical user interface development and event handling.

### Source Files

- Questions.java
- QuizBattleGUI.java

### Topics Covered

- Java Swing
- GUI Development
- Event Handling
- ActionListener
- Object-Oriented Programming

### Summary

The final tutorial combines the knowledge acquired throughout the semester into a graphical quiz application. Users answer a programming question through a simple Java Swing interface and immediately receive feedback based on their selection. This project demonstrates practical GUI development and event-driven programming in Java.

### Expected Output

The application displays a graphical window titled **Programming Quiz Battle**.

Question:

```text
Which keyword creates an object?
```

Options:

```text
new
class
```

Selecting the correct answer displays:

```text
Correct! You defeated the Code Boss!
```

Selecting the incorrect answer displays:

```text
Wrong! Try Again!
```

---

# Technologies Used

- Java
- Java Swing
- Object-Oriented Programming (OOP)
- Visual Studio Code
- Git
- GitHub

---

# Learning Outcomes

Throughout this course, I developed practical experience in:

- Java programming fundamentals
- Object-Oriented Programming principles
- Encapsulation
- Inheritance
- Polymorphism
- Abstraction
- Collections Framework
- File Handling
- Exception Handling
- Event-Driven Programming
- Java Swing GUI Development
- Version Control using Git and GitHub

---

# Reflection

This repository represents my learning journey throughout the Object-Oriented Programming course. Beginning with a simple Java program and gradually progressing to an interactive Java Swing application significantly strengthened both my programming knowledge and problem-solving skills.

Each weekly tutorial introduced new concepts that built upon previous lessons, allowing me to understand how object-oriented principles are applied in real software development. Throughout the semester, I also improved my ability to organize projects, document source code, and manage version control using Git and GitHub.

Completing this portfolio has enhanced my confidence in Java programming and provided a solid foundation for future software development courses and projects.

---

# License

This repository was created for educational purposes as part of the **BIT1123 Object-Oriented Programming** course at **City University Malaysia**.

The source code is intended for academic learning and reference only.
