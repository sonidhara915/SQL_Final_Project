# SQL_Final_Project
📌 Project Overview
The University Management System is a relational database project developed using MySQL. It is designed to manage university information, including departments, students, courses, instructors, and student enrollments.

This project demonstrates how SQL helps organize, manage, retrieve, and analyze academic data efficiently.
🗄️ Database Tables
1. Department Table
Stores department information:
- Department ID
- Department Name
2. Student Table
Stores student details:
- Student ID
- First Name
- Last Name
- Email
- Birth Date
- Enrollment Date
3. Courses Table
Stores course information:
- Course ID
- Course Name
- Department ID
- Credits
4. Instructors Table
Stores instructor details:
- Instructor ID
- First Name
- Last Name
- Email
- Department ID
5. Enrollments Table
Stores student enrollment information:
- Enrollment ID
- Student ID
- Course ID
- Enrollment Date
- Grade
🔗 Database Relationships
- Each course belongs to a department.
- Each instructor is associated with a department.
- Students can enroll in multiple courses.
- Enrollments connect students with courses.
- Primary Keys and Foreign Keys maintain relationships between tables.
📚 SQL Concepts Covered
1. Filtering and Sorting
- WHERE clause
- LIKE operator
- LIMIT
- ORDER BY
2. Aggregate Functions
- COUNT()
- AVG()
- MAX()
3. Joins
- INNER JOIN
- LEFT JOIN
- Multiple table joins
4. Subqueries

- Find students enrolled in courses with more than a specified number of students.

5. Date Functions
- YEAR()
- DATE_SUB()
- CURDATE()
6. String Functions

- CONCAT()

7. Window Functions

- Running Total using COUNT() OVER()

8. CASE Statements

- Classify students as Senior or Junior based on enrollment dates.
🎯 Learning Outcomes
After completing this project, learners can:
- Create and manage relational databases.
- Understand Primary Keys and Foreign Keys.
- Establish relationships between multiple tables.
- Retrieve information using different JOIN operations.
- Perform calculations using aggregate functions.
- Apply subqueries to retrieve specific records.
- Work with date and string functions.
- Use window functions for analytical calculations.
- Apply conditional logic using CASE statements.
🛠️ Tools Used
- MySQL
- SQL
📝 Project Summary
The University Management System provides practical experience in database management and SQL querying. It covers important SQL concepts and helps develop problem-solving and data analysis skills.

This project builds a strong foundation for working with relational databases and pursuing a career in Data Analytics.
