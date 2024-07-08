# MySQL-
Presentation and Hands on project experience.
# MySQL Basics and Functions

## Overview
MySQL is an open-source relational database management system (RDBMS). SQL (Structured Query Language) is a standard programming language used for managing and manipulating relational databases. It allows users to perform tasks such as querying data, updating data, inserting data, deleting data, and creating databases and tables. MySQL is commonly used in web applications, data warehousing, and other data-driven environments due to its reliability, ease of use, and robust feature set.

## Basic Concepts of MySQL
- **Database**: A container for tables and other database objects.
- **Table**: A structured set of data organized in rows and columns.
- **Column**: Represents a specific piece of data in a table.
- **Row**: A record of data within a table.
- **Primary Key**: A unique identifier for each row in a table.
- **Foreign Key**: A field in one table that refers to the primary key in another table.
- **Index**: Improves the speed of data retrieval operations on a table.
- **Queries**: SQL statements used to interact with the database, such as `SELECT`, `INSERT`, `UPDATE`, `DELETE`.
- **Normalization**: Organizing data in a database efficiently to reduce redundancy and improve data integrity.

## Basic Functions in MySQL

### 1. Connecting to a Database
Before performing any operations, you need to connect to the MySQL server and select a database.

USE database_name;
Select * From _Database name_

### 2. **Creating a Database**
Create a new database using the `CREATE DATABASE` statement.

CREATE DATABASE my_database;

### 3. **Creating Tables**

Define the structure of your table using the `CREATE TABLE` statement.

CREATE TABLE employees (
    id INT AUTO_INCREMENT PRIMARY KEY,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    email VARCHAR(100),
    hire_date DATE);
