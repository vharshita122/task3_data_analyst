# task3_data_analyst (Use Cases in Music Database)


 Overview of SQL Queries
SQL is used to manage and manipulate data in relational databases.

Key functions:

Retrieving data

Aggregating and filtering results

Joining tables
Basic SQL with GROUP BY and ORDER BY
GROUP BY: Groups data for aggregation (e.g., summing sales by country).

ORDER BY: Sorts the data based on specified columns (e.g., total sales in descending order).

 SQL Query Breakdown
Aggregating total sales by country, sorted by highest sales.

Helps identify top-performing countries based on sales data.

 Using Joins (INNER, LEFT, RIGHT)
INNER JOIN: Combines only matching rows from both tables.

LEFT JOIN: Retrieves all rows from the left table and matching rows from the right table.

RIGHT JOIN: Retrieves all rows from the right table and matching rows from the left table.

 INNER JOIN
Combines data from related tables where there is a match (e.g., invoice and artist details).

Displays relevant records from both tables.

 LEFT JOIN
Ensures that all records from the left table are included, even if there is no match in the right table (e.g., listing all customers, even without purchases).

 RIGHT JOIN
Retrieves all rows from the right table, even if there's no match in the left table (e.g., displaying all invoices, even without customer data).

 Use Cases in Music Database
INNER JOIN: Combine invoice and artist data to analyze artist performance.

LEFT JOIN: Display all customers, even those without purchases.

RIGHT JOIN: Show all invoices, including those without a customer match.
