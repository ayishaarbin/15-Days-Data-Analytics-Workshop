# Day 04 – SQL Data Querying (DQL)

## Session Overview
Day 4 focused on **data retrieval and analysis using SQL DQL (Data Query Language) commands**, which are essential for every Data Analyst.  

The session covered:
- Querying data from tables
- Sorting and filtering data
- Combining data from multiple tables using joins (LEFT JOIN, RIGHT JOIN)
- Hands-on exercises for real-world analytics scenarios

---

## DQL – Data Query Language
DQL commands are used to **retrieve and analyze data** from database tables.

### SELECT
Used to fetch data from one or more tables.

**Example:**
```sql
SELECT CUST_ID, CUST_NAME, CUST_AGE
FROM CUSTOMER_TB;
WHERE
Used to filter records based on conditions.
Example:
Copy code
Sql
SELECT CUST_ID, CUST_NAME, CUST_AGE
FROM CUSTOMER_TB
WHERE CUST_AGE > 25;
ORDER BY
Used to sort the result set in ascending or descending order.
Example:
Copy code
Sql
SELECT CUST_ID, CUST_NAME, CUST_AGE
FROM CUSTOMER_TB
ORDER BY CUST_AGE DESC;
JOINs – Combining Data from Multiple Tables
JOINs are used to combine rows from two or more tables based on related columns.
LEFT JOIN
Returns all records from the left table and matched records from the right table.
If there is no match, NULL values are returned for the right table.
Example:
Copy code
Sql
SELECT C.CUST_ID, C.CUST_NAME, O.ORDER_ID, O.ORDER_AMOUNT
FROM CUSTOMER_TB C
LEFT JOIN ORDER_TB O
ON C.CUST_ID = O.CUST_ID;
RIGHT JOIN
Returns all records from the right table and matched records from the left table.
If there is no match, NULL values are returned for the left table.
Example:
Copy code
Sql
SELECT C.CUST_ID, C.CUST_NAME, O.ORDER_ID, O.ORDER_AMOUNT
FROM CUSTOMER_TB C
RIGHT JOIN ORDER_TB O
ON C.CUST_ID = O.CUST_ID;
Key Concepts Practiced
Selecting specific columns
Filtering data using conditions
Sorting data in ascending/descending order
Combining data from multiple tables using LEFT and RIGHT joins
Key Learnings – Day 04
Learned how to retrieve data using SELECT
Practiced filtering and sorting data
Understood LEFT JOIN and RIGHT JOIN for combining tables
Gained hands-on experience for real-world analytics scenarios
