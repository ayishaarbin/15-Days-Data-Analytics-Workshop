Day 03 – SQL Fundamentals (DDL, DML & DCL)

## Session Overview
In this session, we continued building strong SQL fundamentals by covering DDL, DML, and DCL commands that are commonly used in real-world data analytics and database operations.

The focus of Day 3 was on modifying data, managing table structures, and controlling database access, along with hands-on practice to understand how these commands work in practical scenarios.

This session is part of our structured learning program designed for:
- Students & Freshers
- Working Professionals
- Career Switchers & Non-IT Backgrounds

---

## SQL Command Types
SQL commands are broadly classified into:
- DDL (Data Definition Language)
- DML (Data Manipulation Language)
- DCL (Data Control Language)

---

## DDL – Data Definition Language
DDL commands are used to define or modify the structure of database objects such as tables.

### ALTER
Used to modify the structure of an existing table.

Example:
```sql
ALTER TABLE CUSTOMER_TB
ADD EMAIL VARCHAR(100);

This command adds a new column called EMAIL to the CUSTOMER_TB table.


---

DML – Data Manipulation Language

DML commands are used to manipulate data stored inside tables.

UPDATE

Used to modify existing records in a table.

Example:

UPDATE CUSTOMER_TB
SET CUST_AGE = 30
WHERE CUST_ID = 1;

This updates the age of the customer whose ID is 1.


---

DELETE

Used to remove specific records from a table.

Example:

DELETE FROM CUSTOMER_TB
WHERE CUST_ID = 1;

This deletes the record of the customer with ID 1.


---

DCL – Data Control Language

DCL commands are used to control access and permissions in the database.

GRANT

Used to provide permissions to users.

Example:

GRANT SELECT, INSERT ON CUSTOMER_TB TO User1;

This grants SELECT and INSERT permissions on the CUSTOMER_TB table to User1.


---

REVOKE

Used to remove permissions from users.

Example:

REVOKE INSERT ON CUSTOMER_TB FROM User1;

This revokes the INSERT permission from User1.


---

Commands Covered in Day 03

ALTER

UPDATE

DELETE

GRANT

REVOKE



---

Key Learnings – Day 03

Learned how to modify table structures using DDL

Practiced updating and deleting data using DML

Understood access control using DCL

Gained practical experience with real-world SQL commands
