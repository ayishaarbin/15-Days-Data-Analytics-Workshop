# Day 02 – SQL Commands (DDL, DML, DCL)

## Overview
Day 2 focused on understanding *core SQL commands* that are used in real-world database and data analytics work.  
We learned how to:
- Create and manage database structures
- Insert, update, and delete data
- Control access and permissions in databases

These commands form the *foundation of SQL* for Data Analysts.

---

## 1. DDL – Data Definition Language
DDL commands are used to *define or modify the structure* of a database and its objects (such as tables).

### CREATE
Used to create a new table in the database.

*Example:*
```sql
CREATE TABLE CUSTOMER_TB (
    CUST_ID INT,
    CUST_NAME VARCHAR(50),
    CUST_AGE INT
);
