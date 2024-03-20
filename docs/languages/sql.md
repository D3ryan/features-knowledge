---
sidebar_position: 3
---

# SQL

**SQL (Structured Query Language)** is a standardized programming language used for managing and manipulating relational databases. It provides a set of commands for querying, updating, and managing data stored in databases. Here's a brief overview:

- **Relational Databases**: SQL is primarily associated with relational database management systems (RDBMS), which organize data into tables with rows and columns. Examples of popular RDBMS include MySQL, PostgreSQL, Oracle, SQL Server, and SQLite.

- **Querying Data**: SQL allows users to retrieve data from a database using queries. The `SELECT` statement is commonly used to retrieve specific columns or rows from one or more tables based on specified criteria.

- **Manipulating Data**: SQL provides commands for inserting, updating, and deleting data in a database. The `INSERT`, `UPDATE`, and `DELETE` statements are used to modify the data stored in tables.

- **Data Definition Language (DDL)**: SQL includes commands for defining and modifying the structure of database objects, such as tables, indexes, and views. DDL statements like `CREATE`, `ALTER`, and `DROP` are used for these purposes.

- **Data Control Language (DCL)**: SQL includes commands for controlling access to data within a database. DCL statements like `GRANT` and `REVOKE` are used to assign or revoke permissions on database objects.

- **Data Manipulation Language (DML)**: SQL includes commands for manipulating data stored in tables. DML statements like `SELECT`, `INSERT`, `UPDATE`, and `DELETE` are used for querying and modifying data.

- **Transaction Control**: SQL supports transaction management, allowing users to ensure the integrity and consistency of data within a database. Commands like `COMMIT`, `ROLLBACK`, and `SAVEPOINT` are used to manage transactions.

SQL is widely used in software development, data analysis, and database administration due to its simplicity, flexibility, and widespread adoption across various database platforms.

### Example

```sql
-- Create a table
CREATE TABLE Employees (
    EmployeeID INT PRIMARY KEY,
    FirstName VARCHAR(50),
    LastName VARCHAR(50),
    Department VARCHAR(50),
    Salary DECIMAL(10, 2)
);

-- Insert data into the table
INSERT INTO Employees (EmployeeID, FirstName, LastName, Department, Salary)
VALUES (1, 'John', 'Doe', 'Engineering', 60000),
       (2, 'Jane', 'Smith', 'Marketing', 55000),
       (3, 'Alice', 'Johnson', 'HR', 50000);

-- Query data from the table
SELECT * FROM Employees;
```
