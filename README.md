📘 Student Record Management System – Java (Lab Assignment 5)

This project implements a complete Student Record Management System using OOP (Abstraction, Inheritance, Interfaces), Exception Handling, File Handling, Multithreading, and Collections — as required in Lab Assignment 5.

Main class: Main

🚀 Features ✔ Object-Oriented Programming

Abstract Class Person

Class Student extending Person

Interface RecordActions

Method Overriding & Encapsulation

✔ Exception Handling

Custom Exception: StudentNotFoundException

Input validation (marks, duplicates, missing data)

try–catch blocks

✔ File Handling

Load and save data using:

BufferedReader

BufferedWriter

Random file access using RandomAccessFile

Persistent storage (students.txt)

✔ Collections

Uses ArrayList to store records

Iterator for traversal

Comparator for sorting by marks

✔ Multithreading

Loader animation using a separate thread (Loader implements Runnable)

✔ Full CRUD System

Add Student

View All Students

Search Student

Update Student

Delete Student

Sort by Marks

Save & Exit

📂 File Format (students.txt)

Stored as comma-separated values:

rollNo,name,email,course,marks

Example:

101,Aryan,aryan@mail.com,B.Tech,92.0

🏗 Class Structure Person (abstract class)

name

email

abstract displayInfo()

Student (extends Person)

rollNo

course

marks

grade

update()

calculateGrade()

RecordActions (interface)

Declares:

addStudent

deleteStudent

updateStudent

searchStudent

viewAllStudents

sortByMarks

StudentManager

Implements all CRUD functionality + file handling + sorting.

Main

Runs the full application menu.

▶️ How to Run

Create an empty file named:

students.txt

Save the Java code as:

Main.java

Compile:

javac Main.java

Run:

java Main

📌 Sample Output ===== Student File Menu =====

Add Student View All Students Search Student Update Student Delete Student Sort by Marks Save & Exit Enter choice: 🎯 Learning Outcomes

Implementing Abstraction & Inheritance

Using Interfaces for system design

Applying custom exceptions

Reading/writing files in Java

Using RandomAccessFile

Using ArrayList, Iterator, Comparator

Threading in Java

Building modular, scalable applications

👨‍💻 Author

Your Name Hamza Yusuf 2401010305 B.Tech CSE K.R. Mangalam University
