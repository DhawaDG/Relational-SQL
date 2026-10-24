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

**Topics covered:**

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

---

## Book References

Key resources used during my learning journey:

- *SQL for Data Scientists* by Renée M. P. Teate

---
## ⬅️⬅️ [Back to Main Profile](https://github.com/DhawaDG)
