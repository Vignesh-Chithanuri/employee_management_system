🧑‍💼 Employee Management System – SQL Project
📌 Project Overview

The Employee Management System is a SQL-based project designed to efficiently manage and analyze employee-related data within an organization. It covers core HR functionalities such as employee records, departmental structure, attendance tracking, performance evaluation, and salary analysis.

This project demonstrates database design, data modeling, and analytical SQL querying, making it ideal for HR analytics, reporting, and decision-making use cases.

🎯 Objectives

Design a structured and normalized employee database

Store and manage employee, department, attendance, and performance data

Perform advanced SQL analysis for HR insights

Enable data-driven decisions using SQL queries

🗂️ Database Schema

The system consists of four core tables:

1️⃣ Departments

Stores department-related information

Example fields: department_id, department_name

2️⃣ Employees

Stores employee personal and job details

Example fields: employee_id, name, department_id, salary, hire_date

3️⃣ Attendance

Tracks daily attendance status for employees

Example fields: attendance_id, employee_id, date, status

4️⃣ Performance

Records yearly performance ratings and remarks

Example fields: performance_id, employee_id, year, rating, remarks

📊 Key Features
✔️ Database Design

Well-structured relational schema

Proper use of primary keys and foreign keys

Maintains data integrity and consistency

✔️ Sample Data

Preloaded sample data for:

Departments

Employees

Attendance records

Performance evaluations

Allows instant testing and analysis

✔️ Analytical SQL Queries

The project includes advanced queries such as:

Department-wise average salary

Employee names with corresponding department names

Employees with the highest attendance in the last 30 days

Top-performing employees by rating for a specific year

Average performance rating per department

Salary categorization (Low / Medium / High)

Salary ranking within each department using window functions

🧪 Sample SQL Queries Included

Department-wise average salary

Employee list with department names

Employees with highest attendance in the last 30 days

Top performers by rating for a given year

Average performance rating per department

Salary range classification

Department-wise salary ranking

⚙️ How to Use
🔧 Setup

Open your SQL environment (MySQL / MariaDB recommended)

Run the SQL script:

Employee_Management_System_Project.sql


Tables and sample data will be created automatically

📈 Analysis

Execute the provided analytical queries

Modify or extend queries for custom HR reports

Use the database for practice or real-world simulations

📁 Project Structure
Employee_Management_System_Project.sql


Contains:

Table creation scripts

Sample data insertion

Analytical SQL queries

💡 Use Cases

HR analytics and reporting

Employee attendance monitoring

Performance evaluation analysis

Salary benchmarking

Department-wise workforce insights

🛠️ Tools & Technologies

SQL (MySQL / MariaDB compatible)

Relational Database Design

Window Functions

Aggregate Functions

🚀 Future Enhancements

Add employee promotions history

Monthly attendance reports

Role-based access control

Integration with Power BI / Tableau
Departmental insights
