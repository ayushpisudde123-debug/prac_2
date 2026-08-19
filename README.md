Marksheet Management System

Project Overview

Marksheet Management System is a simple MySQL database project used to store and calculate student marks.

The project stores marks for different subjects and calculates the total marks and percentage of each student.

Database

Database Name: marksheet

Table

The project contains one table:

student

Student Table

The student table stores student information and subject marks.

Columns:

id – Unique student ID
name – Student name
maths – Marks obtained in Mathematics
science – Marks obtained in Science
english – Marks obtained in English

Sample Students

Rahul
Varun
Ayush

Features

Store student details
Store subject marks
Calculate total marks
Calculate percentage
Display student marksheet

SQL Operations

The project uses INSERT statements to add student records.

The SELECT query is used to calculate total marks and percentage.

Example:

SELECT
id,
name,
maths,
science,
english,
(maths + science + english) AS total,
ROUND((maths + science + english) / 3, 2) AS percentage
FROM student;

Technologies Used

MySQL
SQL
MySQL Workbench / OneCompiler

Project Objective

The main objective of this project is to practice MySQL and learn how to store student marks and perform calculations using SQL.

Future Improvements

Add more subjects
Add grades
Add pass/fail status
Add student attendance
Add rank calculation
Add multiple classes
Add student details such as roll number and department

Conclusion

This is a beginner-friendly MySQL project for creating a simple student marksheet. It demonstrates database creation, table creation, data insertion, and calculation using SQL.
