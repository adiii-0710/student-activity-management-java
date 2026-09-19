# Student Activity Management System

A simple Java console-based application that manages student attendance and marks. The program validates user input, checks examination eligibility based on attendance, and displays a performance category based on marks.

## Features

- Accepts attendance percentage from the user
- Validates attendance between 0 and 100
- Accepts marks from the user
- Validates marks between 0 and 100
- Checks examination eligibility
- Displays performance category
- Provides a menu-driven interface
- Uses `switch` statements
- Uses nested `if-else` conditions
- Allows the user to exit the program

## Technologies Used

- Java
- Scanner Class
- Conditional Statements
- Switch Case
- While Loop

## Attendance Eligibility

The program checks attendance using the following condition:

```text
Attendance >= 75% → Eligible
Attendance < 75%  → Not Eligible
Performance Categories
90 - 100 → Excellent
70 - 89  → Good
60 - 69  → Average
0 - 59   → Needs Improvement

```
How to Run
```
Compile the program:

javac StudentActivityManagement.java

Run the program:

java StudentActivityManagement
Example
Enter attendance percentage (0-100): 82
Enter marks (0-100): 76
```

===== Student Activity Management System =====
```
1. Check Attendance Eligibility
2. View Performance Category
3. Exit
Enter your choice: 1
```
The student is eligible to appear for the examination.

===== Student Activity Management System =====
```
1. Check Attendance Eligibility
2. View Performance Category
3. Exit
Enter your choice: 2

Performance Category: Good

```
