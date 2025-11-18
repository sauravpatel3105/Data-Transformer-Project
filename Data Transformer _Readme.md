# Data Transformer SQL Project

This project demonstrates the creation and manipulation of a MySQL
database named **data_transformer**. It includes tables, inserts, joins,
window functions, date functions, string functions, and conditional
logic.

------------------------------------------------------------------------

## 📌 Database Structure

### **1. Customers Table**

Stores customer details: - CustomerID (PK) - Firstname - Lastname -
Email - RegistrationDate

### **2. Orders Table**

Stores order information: - OrderID (PK) - CustomerID (FK → Customers) -
OrderDate - TotalAmount

### **3. Employees Table**

Stores employee records: - EmployeeID (PK) - Firstname - Lastname -
Department - HireDate - Salary

------------------------------------------------------------------------

## 📌 SQL Features Included

### ✔ Table Creation & Insertion

-   `CREATE TABLE`
-   `INSERT INTO`
-   Foreign key constraints

### ✔ Joins

-   `INNER JOIN`
-   `LEFT JOIN`
-   `RIGHT JOIN`
-   Full outer join using `UNION`

### ✔ Subqueries

Examples: - Orders with TotalAmount above average - Employees earning
above average salary

### ✔ Date Functions

-   `YEAR()`, `MONTH()`
-   `DATEDIFF()`
-   `DATE_FORMAT()`

### ✔ String Functions

-   `CONCAT()`
-   `REPLACE()`
-   `UPPER()`, `LOWER()`
-   `TRIM()`

### ✔ Window Functions

-   `SUM() OVER()` → Running totals
-   `RANK() OVER()` → Ranking by amount

### ✔ CASE Expressions

Used for: - Discount calculations\
- Salary categorization (High, Medium, Low)

------------------------------------------------------------------------

## 📌 How to Use

Run these SQL scripts using: - **MySQL Workbench** - **XAMPP
phpMyAdmin** - **MySQL command-line**

Each query is standalone and useful for practice.

------------------------------------------------------------------------

## 📌 Author

SQL Practice Project -- Data Transformer\
Designed for students learning SQL from basics to advanced concepts.
