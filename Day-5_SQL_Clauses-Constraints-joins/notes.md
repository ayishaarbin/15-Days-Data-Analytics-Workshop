Day 05 – SQL Clauses, Constraints & Joins

## Session Overview
Day 5 focused on **data analysis and integrity** using SQL clauses, constraints, and joins.  
We practiced:
- Filtering and grouping data using clauses
- Maintaining data accuracy using constraints
- Combining data from multiple tables using joins

Hands-on exercises helped understand real-world application of these concepts.

---

## SQL Clauses
SQL clauses define conditions or operations to manipulate and retrieve data effectively.

### WHERE Clause
Filters individual rows from a table based on specified conditions.

**Example:**
```sql
SELECT * 
FROM CUSTOMER_TB
WHERE CUST_AGE > 25;
Retrieves customers older than 25.
GROUP BY Clause
Groups rows with the same values in specified columns into summary rows. Useful for aggregate functions.
Example:
Copy code
Sql
SELECT CITY, COUNT(*) AS TOTAL_CUSTOMERS
FROM CUSTOMER_TB
GROUP BY CITY;
Groups customers by city and counts them.
HAVING Clause
Filters groups of rows after aggregation (applied with GROUP BY).
Example:
Copy code
Sql
SELECT CITY, COUNT(*) AS TOTAL_CUSTOMERS
FROM CUSTOMER_TB
GROUP BY CITY
HAVING COUNT(*) > 5;
Shows cities with more than 5 customers.
SQL Constraints
Constraints maintain data accuracy, consistency, and integrity in a database.
Types of Constraints
NOT NULL: Column cannot have NULL values.
UNIQUE: Ensures all values in a column are distinct.
PRIMARY KEY: Uniquely identifies each row; always NOT NULL & UNIQUE.
FOREIGN KEY: Links two tables ensuring referential integrity.
CHECK: Ensures column values meet a specific condition.
DEFAULT: Assigns a default value if none is provided.
Example:
Copy code
Sql
CREATE TABLE CUSTOMER_TB (
    CUST_ID INT PRIMARY KEY,
    CUST_NAME VARCHAR(50) NOT NULL,
    CUST_AGE INT CHECK (CUST_AGE >= 18),
    CITY VARCHAR(50) DEFAULT 'Unknown'
);
SQL Joins
Joins combine rows from two or more tables based on related columns.
INNER JOIN
Returns only rows with matching values in both tables.
LEFT (OUTER) JOIN
Returns all records from the left table, with matched records from the right table. NULL for unmatched right-side rows.
RIGHT (OUTER) JOIN
Returns all records from the right table, with matched records from the left table. NULL for unmatched left-side rows.
FULL (OUTER) JOIN
Returns all records when there is a match in either table. NULL for non-matching rows.
Example:
Copy code
Sql
-- INNER JOIN
SELECT C.CUST_ID, C.CUST_NAME, O.ORDER_ID
FROM CUSTOMER_TB C
INNER JOIN ORDER_TB O
ON C.CUST_ID = O.CUST_ID;

-- LEFT JOIN
SELECT C.CUST_ID, C.CUST_NAME, O.ORDER_ID
FROM CUSTOMER_TB C
LEFT JOIN ORDER_TB O
ON C.CUST_ID = O.CUST_ID;

-- RIGHT JOIN
SELECT C.CUST_ID, C.CUST_NAME, O.ORDER_ID
FROM CUSTOMER_TB C
RIGHT JOIN ORDER_TB O
ON C.CUST_ID = O.CUST_ID;

-- FULL JOIN
SELECT C.CUST_ID, C.CUST_NAME, O.ORDER_ID
FROM CUSTOMER_TB C
FULL OUTER JOIN ORDER_TB O
ON C.CUST_ID = O.CUST_ID;


