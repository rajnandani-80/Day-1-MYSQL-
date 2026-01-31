# Student Database Management using MySQL

## 📌 Project Overview
This project demonstrates basic MySQL database operations using SQL commands.  
It covers database creation, table creation, data insertion, table alteration, and data retrieval.

---

## 🛠️ Technologies Used
- MySQL Community Server
- SQL

---

## 📂 Database Details
- **Database Name:** EFLOWDATABASE
- **Table Name:** STUDENTS

---

## 🧱 Table Structure
The `STUDENTS` table contains the following columns:

| Column Name | Data Type      | Description              |
|------------|----------------|--------------------------|
| ID         | INT (Primary Key) | Unique student ID        |
| NAME       | VARCHAR(50)    | Student name             |
| AGE        | INT            | Student age              |
| EMAIL      | VARCHAR(100)   | Student email address    |
| ADDRESS    | VARCHAR(50)    | Student address (optional) |

---

## 🧪 SQL Operations Performed

### 1. Create Database
```sql
CREATE DATABASE EFLOWDATABASE;
2. Use Database
USE EFLOWDATABASE;
3. Create Table
CREATE TABLE STUDENTS (
    ID INT PRIMARY KEY,
    NAME VARCHAR(50),
    AGE INT,
    EMAIL VARCHAR(100)
);
4. Insert Records
INSERT INTO STUDENTS (ID, NAME, AGE, EMAIL) VALUES
(1, 'SHIVAM', 20, 'SHIVAM@GMAIL.COM'),
(2, 'PRIYAM', 30, 'PRIYAM@GMAIL.COM'),
(3, 'AADIT', 40, 'AADIT@GMAIL.COM'),
(4, 'RAM', 45, 'RAM@GMAIL.COM');
5. Alter Table
ALTER TABLE STUDENTS
ADD ADDRESS VARCHAR(50);
6. View Data
SELECT * FROM STUDENTS;
🎯 Learning Outcomes
Understanding database and table creation

Using PRIMARY KEY constraints

Inserting multiple records

Modifying table structure using ALTER

Retrieving data using SELECT queries

📌 Note
This repository contains only correct and clean SQL queries.
Errors faced during practice were resolved and are not included in the final submission.

👩‍💻 Author
Rajnandani Singh