# Relational SQL: A Foundation for Data Analysis

This section of my portfolio documents my journey in mastering Relational SQL. As a foundational skill for any data professional, a deep understanding of SQL is critical for efficiently querying, manipulating, and analyzing data from relational databases. The topics and projects here demonstrate my proficiency in crafting complex queries for data extraction and business intelligence.

---

## Hands-on Projects

| SN | SQL Projects |
|:---:|:---|
| 1 | **[E-Commerce Sales Analysis with SQL](https://github.com/DhawaDG/DhawaDG-E-Commerce-Sales-Analysis-with-SQLS)** |


---

## Concepts Covered

- **SELECT, WHERE, ORDER BY:** (10h)
- **JOINs:** INNER, LEFT, RIGHT (12h)
- **GROUP BY, Aggregation:** (8h)
- **Subqueries & Nested SELECT:** (10h)
- **Window Functions:** (12h)
- **CTEs (WITH clause):** (8h)
- **Date/Time Functions:** (6h)
- **CASE Statements:** (6h)

---

## Handwritten Notes PDF

A collection of my detailed handwritten notes and summaries on these topics is available in PDF format.  

> **Note on Viewing PDFs on GitHub:**  
> If you encounter an "Unable to render code block" or preview error when opening a **📄 View PDF on GitHub** link, please reload the page or use the **⬇️ Download PDF** link right below it.

### 1. Core Database Fundamentals & SQL Commands
| Topics Covered | Page |
| :--- | :--- |
| SQL command categories: DDL, DML, DCL, TCL and their commands | `page 1` |
| SQL structure: databases, tables, data, rows and columns (RDBMS) | `page 2` |
| Keys: primary key (unique, not null, only one per table) with example table | `page 2` |
| Primary key syntax (CREATE TABLE students) | `page 3` |
| Foreign key: definition, child and parent tables | `page 3` |
| Foreign key syntax (FOREIGN KEY ... REFERENCES) | `page 4` |
| Example: students (child) and cities (parent) tables | `page 4` |
| Tutorial 2: SHOW DATABASES | `page 5` |
| MySQL string datatypes (CHAR, VARCHAR, TEXT, BLOB, ENUM, SET) | `page 5` |
| MySQL numeric datatypes (BIT, INT, BIGINT, BOOL, FLOAT, DOUBLE, DECIMAL) | `page 5` |
| MySQL date and time datatypes (DATE, DATETIME, TIMESTAMP, TIME, YEAR) | `page 6` |
| Basics of SQL: understanding databases | `page 7` |
| Relational vs non-relational databases: structure, scalability, strength | `page 7` |
| Relational vs non-relational: storage, schema, performance, examples | `page 8` |
| Basic SQL commands: the SELECT statement and its syntax | `page 9` |
| Selecting a whole table, specific columns, renaming columns (AS) | `page 9` |
| WHERE syntax with SELECT | `page 9` |
| WHERE comparison operators (=, >, <, >=, <=, <>, BETWEEN, LIKE, IN) | `page 10` |
| Fundamental syntax structure of a SELECT query (WHERE, GROUP BY, HAVING, ORDER BY) | `page 11` |
| Selecting columns and limiting rows with LIMIT | `page 11` |
| ORDER BY: sorting results (ASC default, DESC) | `page 11` |
| Introduction to simple inline calculation (heading only, page is otherwise blank) | `page 12` |
| Creating tables (CREATE TABLE personal) | `page 13` |
| Inserting values into a table | `page 13` |
| Inserting multiple rows (syntax) | `page 13–14` |
| Multi-row insert implementation | `page 14` |
| List of constraints in MySQL (NOT NULL, UNIQUE, DEFAULT, CHECK, FOREIGN KEY, PRIMARY KEY) | `page 14` |
| Data table without constraints (example of bad data) | `page 14` |
| Problems from missing constraints (missing values, age under 18, duplicate phone, same city) | `page 15` |
| CREATE TABLE syntax with constraints (NOT NULL, CHECK, UNIQUE, DEFAULT) | `page 15` |
| How to show data from tables with SQL | `page 16` |
| SELECT syntax: SELECT columns and SELECT * | `page 16` |
| Exercise: three customer table queries | `page 17` |
| Solution: create the customer_database schema and customer_info table | `page 17` |
| The WHERE clause: filtering SELECT results (syntax and implementation) | `page 18` |
| Filtering on multiple conditions: syntax | `page 18` |
| Implement 1: OR | `page 18` |
| Implement 2: AND (returns no values) | `page 19` |
| Implement 3 and 4: not equal (!=) | `page 19` |
| Implement 5 and 6: in between (comparison operators and BETWEEN) | `page 19` |
| Truth table for AND, OR, AND NOT | `page 20` |
| Implement 7: IN | `page 20` |
| Implement 8: NULL (heading only, no content) | `page 20` |
| Subquery definition (can appear in WHERE, FROM or SELECT) | `page 21` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Relational-SQL/blob/main/chapter1SQL-1-21%20(1).pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Relational-SQL/raw/refs/heads/main/chapter1SQL-1-21%20(1).pdf)




### 2. SQL Subqueries & Different Types of Subqueries

| Topics Covered | Page |
| :--- | :--- |
| What a subquery is; average salary example (two approaches) | `page 1` |
| Advantages of subqueries | `page 2` |
| Types of subqueries (scalar, multiple row, correlated) | `page 2` |
| Scalar subquery and its syntax | `page 2–3` |
| Subquery with JOIN (implementation) | `page 3` |
| Why use table aliases | `page 3` |
| Self-join and why aliases are necessary | `page 3–5` |
| Subquery alias, how the JOIN works, role of ON | `page 6` |
| Subquery as a virtual table | `page 7–8` |
| What happens during the join, important points | `page 8` |
| Why use a subquery with JOIN (dynamic calculation, reusability) | `page 9` |
| Dot notation and disambiguating column names | `page 10–11` |
| Multiple row subquery (highest salary per department) with IN | `page 12–13` |
| Single column, multiple row subquery with NOT IN | `page 14` |
| Correlated subquery: outer query, inner query, example calculation | `page 15–16` |
| Generalization and key points (dynamic matching, e1/e2) | `page 17` |
| Waiter analogy and code | `page 18` |
| Explanation 2 (classroom analogy) and simplified code meaning | `page 19–20` |
| NOT EXISTS: breakdown, school analogy, conditions, example tables, execution, output | `page 21–24` |
| Subqueries in FROM (derived tables), products above average sales | `page 25–30` |
| Why the aliases n and avg_sales are needed | `page 28–30` |
| Subquery in SELECT with CASE (remarks column) | `page 31–34` |
| Subquery in HAVING (stores above average quantity) | `page 35–39` |
| Primary and foreign key practical (city and personal tables) | `page 40–41` |
| Inner join of personal and city, WHERE and ORDER BY | `page 41` |
- [📄 View PDF on GitHub](https://github.com/DhawaDG/Relational-SQL/blob/main/subqueries.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Relational-SQL/raw/refs/heads/main/subqueries.pdf)

### 3. SQL Data Retrieval & Manipulation

| Topics Covered | Page |
| :--- | :--- |
| Aggregate functions (COUNT, MAX, MIN, SUM, AVG) and SELECT syntax | `page 1` |
| COUNT aggregate: total employees, COUNT() note | `page 1` |
| COUNT(DISTINCT dept_name) | `page 2` |
| MAX aggregate (highest salary) | `page 2` |
| MIN aggregate (lowest salary) | `page 2` |
| Why MAX and MIN return the same result | `page 2` |
| SUM aggregate (total expense) | `page 3` |
| AVG aggregate (average salary) | `page 3` |
| Purpose of GROUP BY | `page 4` |
| Total spending per customer per market date, without GROUP BY (duplicates) | `page 4` |
| Grouping by market_date and customer_id with SUM(price) | `page 4–5` |
| Explanation of GROUP BY, SUM, ORDER BY | `page 5` |
| Alternative using DISTINCT (unique combinations) | `page 5` |
| Group summary: count of items purchased (COUNT()) | `page 6` |
| Group summary: sum of quantities purchased (SUM(quantity)) | `page 6` |
| Group summary: count of distinct products (COUNT(DISTINCT product)) | `page 7` |
| Combining multiple summaries in a single query | `page 7` |
| Buyer, supplier and purchase tables, primary and foreign keys | `page 8` |
| Total spending per customer on each day (SUM(quantity * cost_per_unit)) | `page 9` |
| Total spending per customer at each vendor | `page 10` |
| Total spending by each customer | `page 11` |
| Detailed report: customer and vendor details with LEFT JOIN | `page 12` |
| How JOINs create a combined dataset | `page 12–13` |
| Step-by-step execution of the join query | `page 13` |
| Why you can use columns from other tables in SELECT | `page 13–14` |
| Example walkthrough (buyer, purchase and supplier tables) | `page 14` |
| What happens when the query is executed, and the combined dataset | `page 15` |
| Final output of the customer and vendor report | `page 16` |
| HAVING: purpose, difference from WHERE, typical use cases | `page 17` |
| Regional sales_data table | `page 17` |
| HAVING SQL code (total_revenue >= 15000), ORDER BY and output | `page 18` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Relational-SQL/blob/main/dataretrievalandmanipulations.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Relational-SQL/raw/refs/heads/main/dataretrievalandmanipulations.pdf)

### 4. SQL Joins
  
| Topics Covered | Page |
| :--- | :--- |
| Database relationships: one-to-many (customer and purchases), primary and foreign keys (already covered) | `page 1` |
| Inner join: Venn diagram, description, when to use, example | `page 1` |
| Inner join syntax | `page 2` |
| Left join: Venn diagram, description (unmatched right-side rows become NULL), example | `page 2` |
| Left join syntax | `page 3` |
| Right join: Venn diagram, description, example | `page 3` |
| Right join syntax | `page 4` |
| Sample database sql_joins: employees and department tables | `page 4` |
| Left join query (employees with department) | `page 4–5` |
| Left join output (Charlie has a NULL department) | `page 5` |
| Right join query and output (the unmatched IT department shows NULL employee) | `page 5` |
| Inner join query | `page 5` |
| Inner join output (Alice and Bob only) | `page 6` |
| Common pitfalls when filtering joined data | `page 6–7` |
| Sample customers and customer_purchases tables (with foreign key) | `page 6` |
| Pitfall: a WHERE filter on a right-table column turns a left join into an inner join | `page 7` |
| Query 1 (problem): WHERE cp.market_date <> '2025-01-15' drops customers with no purchases | `page 7` |
| Query 2 (fix): WHERE (... <> '2025-01-15' OR cp.market_date IS NULL) with DISTINCT | `page 8` |
| Why query 2 works, and outputs of both queries | `page 8` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Relational-SQL/blob/main/sqljoins.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Relational-SQL/raw/refs/heads/main/sqljoins.pdf)

### 5. SQL Window Functions

| Topics Covered | Page |
| :--- | :--- |
| Window functions: ROW_NUMBER() definition and key points (partitioning, ordering, subquery for filtering) | `page 1` |
| vendor_inventory table (sample data) | `page 2` |
| Query to rank products by price per vendor | `page 2` |
| Query breakdown: ROW_NUMBER(), OVER, PARTITION BY vendor_id, ORDER BY original_price DESC, AS price_rank | `page 3–4` |
| How it works: partitioning, ordering, row numbering, final output | `page 4–5` |
| Query to find the most expensive product per vendor (subquery with ranked_inventory) | `page 6` |
| Explanation of the nested query (price_rank = 1, ORDER BY vendor_id) | `page 7–8` |
| Role of OVER: sports race analogy (age groups and finish times) | `page 8–9` |
| Why not use GROUP BY instead (it loses row details) | `page 9` |
| RANK and DENSE_RANK: definitions and gaps in ranking | `page 10` |
| ROW_NUMBER for comparison (unique ranks, no ties) | `page 10` |
| Key differences between RANK, DENSE_RANK and ROW_NUMBER (school competition analogy) | `page 11` |
| vendor_inventory1 table (with price ties) | `page 11` |
| RANK() query, output and explanation | `page 12–13` |
| DENSE_RANK() query, output and explanation | `page 12–14` |
| ROW_NUMBER() query and output on the tied data | `page 14` |
| NTILE: what it does, syntax, how it works (even distribution, uneven rows) | `page 15` |
| NTILE with ties, when to use it (percentiles, quartiles), vendor_inventory2 table | `page 16` |
| NTILE into 4 groups (quartiles): query start | `page 16` |
| NTILE(2) with PARTITION BY vendor_id, output and explanation | `page 17` |
| Aggregate window functions: what they do, syntax, common use cases | `page 18` |
| AVG() as a window function (average price by market date), with hand calculation | `page 19` |
| AVG() output, table vendor_inventory3 | `page 20` |
| COUNT() as a window function (PARTITION BY market_date, vendor_id) | `page 21` |
| Why COUNT(product_id) doesn’t count one product, and conditional COUNT(CASE WHEN ...) | `page 22` |
| COUNT() output | `page 23` |
| SUM() as a window function (running total) and explanation | `page 23` |
| SUM() running total output | `page 24` |
| LAG() and LEAD(): definitions, syntax, parameters (column, offset, PARTITION BY, ORDER BY) | `page 25` |
| Use cases for LAG and LEAD | `page 26` |
| vendor_booth_assignments table | `page 26` |
| employee_salaries table | `page 27` |
| LAG() to compare previous salaries: query | `page 27` |
| How LAG() works in the query (partition, order, offset, final order) | `page 27–28` |
| LAG() output (first row is NULL) | `page 28` |
| LEAD() to see future salaries: query and output | `page 29` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Relational-SQL/blob/main/windowfunctions.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Relational-SQL/raw/refs/heads/main/windowfunctions.pdf)


### 5. SQL Common Tables Expressions(CTEs) & Temporary Table

| Topics Covered | Page |
| :--- | :--- |
| Common Table Expressions (CTEs): definition (WITH, temporary result set) | `page 1` |
| When to use CTEs (recursive queries, reusing a subquery, readability) | `page 1` |
| employees sample table (7 rows with department, manager and salary) | `page 1` |
| CTE limitation: you can’t UPDATE, DELETE or INSERT on it | `page 2` |
| department_avg CTE joined with employees (salary above the department average) | `page 2` |
| CTE example output (Alice and David) | `page 2` |
| Why department_avg behaves like a table (virtual table, join works) | `page 2–3` |
| CTE vs user-defined function comparison table (behavior, scope, use case, joinable) | `page 3` |
| How the CTE example works, step by step | `page 3` |
| Temporary tables: definition, persistence, when to use | `page 4` |
| Temporary table Example 1 (high_salary_employees) and how it works | `page 4` |
| Temporary table Example 2 (department_salaries for performance) | `page 5` |
| Key differences: CTEs vs temporary tables (scope, usage, performance, persistence) | `page 5` |
| Performance optimization: indexing for faster querying (what an index is) | `page 6` |
| Types of indexes: primary, single-column, composite, unique, full-text, hash, clustered and non-clustered, B-tree | `page 6` |
| When to use indexes | `page 7` |
| Index best practices (avoid over-indexing, remove unused indexes, composite indexes) | `page 7` |
| Query profiling and analysis with EXPLAIN | `page 7` |
| users sample table | `page 8` |
| Index workflow example: query without index, EXPLAIN, CREATE INDEX idx_email, repeat EXPLAIN | `page 8` |
| Combining indexing and EXPLAIN: identify slow queries, analyze, add or modify indexes, re-analyze | `page 9` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Relational-SQL/blob/main/cte%26temp_table%20(1).pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Relational-SQL/raw/refs/heads/main/cte%26temp_table%20(1).pdf)

### 5. SQL Time and Date Functions
| Topics Covered | Page |
| :--- | :--- |
| Date and time functions: setting datetime field values | `page 1` |
| Datetime fields (date and time in one column) | `page 1` |
| STR_TO_DATE() (format string %Y-%m-%d %h:%i %p) | `page 1` |
| CONCAT() to merge date and time strings | `page 1` |
| %Y vs %y (4-digit vs 2-digit year) | `page 2` |
| market_date_info table, and creating datetime_demo with STR_TO_DATE(CONCAT(...)) | `page 2` |
| Query output (start and end datetime columns) | `page 2–3` |
| Explanation of the query, why the space ' ' in CONCAT, whether CONCAT turns dates into strings, why STR_TO_DATE is needed | `page 3` |
| EXTRACT and date-part functions: datetime extraction, EXTRACT syntax | `page 4` |
| DATE() and TIME() functions, use cases | `page 4` |
| datetime_demo1 table | `page 5` |
| EXTRACT for day, month, year, hour and minute, with output | `page 5` |
| DATE() and TIME() query and output | `page 5–6` |
| Filtering using extracted parts (EXTRACT(YEAR ...) and EXTRACT(MONTH ...)) | `page 6` |
| DATE_ADD and DATE_SUB: data calculations, syntax, examples | `page 7` |
| Negative intervals (DATE_ADD with a negative interval equals DATE_SUB) | `page 8` |
| DATE_ADD query and output (add 30 minutes and 30 days) | `page 8` |
| DATEDIFF: function, syntax, use cases, nested queries | `page 9` |
| datetime_demo3 table | `page 9` |
| DATEDIFF with a nested query (MIN and MAX, alias x) and breakdown | `page 10–11` |
| DATEDIFF output (first market to last market) | `page 11` |
| movie_bookings and employee_records tables | `page 11` |
| Employee tenure and time since last promotion (CURDATE(), DATEDIFF) | `page 12` |
| Explanation of the query and output | `page 12` |
| Employees not promoted in the last 2 years (> 730 days) | `page 13` |
| Employees promoted within 30 days of joining (no rows returned) | `page 13–14` |
| Why you can’t use an alias in WHERE (it runs before SELECT) | `page 13–14` |
| TIMESTAMPDIFF: function, syntax, supported intervals, use cases | `page 15` |
| market_datetime table | `page 15` |
| TIMESTAMPDIFF query (hours and minutes) and output | `page 16` |
| Exploring multiple tables: aggregating, filtering, use cases | `page 17` |
| customer_purchases table | `page 18` |
| Aggregation query (SUM(quantity), SUM(quantity * cost), GROUP BY, WHERE) | `page 18` |
| Output and explanation of the totals | `page 19` |


- [📄 View PDF on GitHub](https://github.com/DhawaDG/Relational-SQL/blob/main/time%26datefunctions%20(1).pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Relational-SQL/raw/refs/heads/main/time%26datefunctions%20(1).pdf)


### 6. SQL Unions

| Topics Covered | Page |
| :--- | :--- |
| More advanced query structures: UNION vs UNION ALL | `page 1` |
| Use cases for unions | `page 1` |
| Requirements (matching column count, order and data type; names come from the first query) | `page 1` |
| sales_2022 and sales_2023 sample tables | `page 1` |
| Combining data with UNION (query with ORDER BY sale_date) and output | `page 2` |
| Advanced example with a CTE and UNION ALL: sales_combined (adds sale_year with YEAR(sale_date)) | `page 3` |
| top_products CTE (SUM(quantity), RANK() OVER (PARTITION BY sale_year ...)) | `page 3–4` |
| Final query (WHERE quantity_rank = 1) | `page 4` |
| sales_combined and top_product intermediate results | `page 4` |
| Final output (top product per year: 101 in both) | `page 5` |
| Self-join to determine to-date maximum: what a self-join is | `page 6` |
| Three steps (summarize with a CTE, self-join to compare with previous dates, MAX() and CASE to flag a new record) | `page 6` |
| employee_salaries sample table | `page 6` |
| Query: employee_salary_summary CTE, LEFT JOIN on earlier dates, MAX(prev.salary_amount), CASE ... 'Yes'/'No' | `page 7` |
| Output: previous max salary and whether each row is a new record | `page 8` |
| Counting new vs returning customers by week (heading only) | `page 9` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Relational-SQL/blob/main/UnionSQLpdf.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Relational-SQL/raw/refs/heads/main/UnionSQLpdf.pdf)


---

## Book References

Key resources used during my learning journey:

- *SQL for Data Scientists* by Renée M. P. Teate

---
## ⬅️⬅️ [Back to Main Profile](https://github.com/DhawaDG)
