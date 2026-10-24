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
| Core Database Fundamentals | `page 1` |
| SQL Commands (DDL, DML, DCL, TCL) | `page 2` |
| Database Structures (Tables, Rows, Columns, RDBMS) | `page 2` |
| Primary Keys and Foreign Keys | `page 2` |
| Connecting to a Database | `page 2` |
| Executing SQL Queries | `page 2` |
| Creating Tables using CREATE TABLE | `page 2` |
| SQL Data Types (Numeric, String, Date, Boolean, and Binary Types) | `page 5` |
| Creating and Dropping Databases and Tables | `page 5 - 21` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Relational-SQL/blob/main/chapter1SQL-1-21%20(1).pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Relational-SQL/raw/refs/heads/main/chapter1SQL-1-21%20(1).pdf)




### 2. SQL Subqueries & Different Types of Subqueries

| Topics Covered | Page |
| :--- | :--- |
| Introduction to SQL Subqueries | `page 1` |
| Advantages of Subqueries | `page 2` |
| Scalar Subqueries | `page 2` |
| Multiple-Row Subqueries | `page 12` |
| Single-Column, Multiple-Row Subqueries | `page 12` |
| Inner Queries and Outer Queries | `page 12 page 15 page 21 page 25 ` |
| Multiple-Column, Multiple-Row Subqueries | `page 13` |
| Correlated Subqueries | `page 15` |
| Table Aliases in Subqueries | `page 28  ` |
| Using Subqueries in the `SELECT` Clause | `page 31` |
| Using Subqueries in the `HAVING` Clause | `page 35` |
| Using Aggregate Functions in Subqueries (`AVG()`, `MAX()`, `SUM()`) | `page 31 to page 38` |
| Using `IN` with Multiple-Column Subqueries | `page 12-13 (query on 12, inner/outer explanation on 13)` |
| Using `NOT IN` with Subqueries | `page 14` |
| Using `NOT EXISTS` with Correlated Subqueries | `page 21-24 (query and breakdown 21-22, conditions and example tables 23, execution and final output 24)` |
| Subqueries as Virtual Tables (Derived Tables) | `page 7-8 (virtual table concept). Derived tables with aliases n and avg_sales are on page 25-30.` |
| Column References and Dot Notation | `page 31` |
| Using Subqueries with `JOIN` | `page 3 (syntax and implementation), page 6-9 (how the join and ON work, why use a subquery with a join)` |
| Using Subqueries in the `WHERE` Clause | `page 1 (the salary > (select avg(salary)...) example). Correlated WHERE subqueries are on page 15-18. ` |
| Using `CASE` Statements with Subqueries | `page 31-34 (question and SELECT/CASE breakdown 31-32, example walkthrough 33, final SQL code 34) ` |
| Finding Employees Earning More Than the Average Salary | `page 1 (question and both approaches). The join version is on page 3, and its explanation on page 6-9.` |
| Finding Employees Earning More Than Their Departmental Average Salary | `page 15-20 (correlated subquery with e1/e2: query on page 15, example calculation on page 16, key points on page 17, analogy and code on page 18, explanations on page 19-20)` |
| Finding the Highest-Paid Employees in Each Department | `page 12-13 (query on 12, inner/outer query explanation and IN clause on 13)` |
| Finding Departments Without Employees | `	page 14 (NOT IN version), 21-24 (NOT EXISTS version)` |
| Finding Products with Total Sales Above Average | `page 25-30 (query 25, results and average calculation 26, JOIN and final output 27, why it works and alias n 28, why two aliases 29, summary 30)` |
| Finding Stores Selling More Than the Average Quantity | `page 35-39 (HAVING with a subquery: query 35, clause explanation 36, how it works and example data 37, step-by-step calculation 38, key points 39)` |
- [📄 View PDF on GitHub](https://github.com/DhawaDG/Relational-SQL/blob/main/subqueries.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Relational-SQL/raw/refs/heads/main/subqueries.pdf)

### 3. SQL Data Retrieval & Manipulation

**Topics covered:**

- Introduction to SQL Data Retrieval and Aggregation
- Aggregate Functions: `COUNT()`, `MAX()`, `MIN()`, `SUM()`, and `AVG()`
- Using Aggregate Functions in `SELECT` Queries
- Counting Total Employees
- Counting Distinct Departments with `COUNT(DISTINCT ...)`
- Finding Maximum and Minimum Salaries
- Calculating Total Salary Expenditure
- Calculating Average Salary
- Understanding Why `MAX()` and `MIN()` Can Return the Same Value
- Introduction to the `GROUP BY` Clause
- Grouping Records by Multiple Columns
- Using `GROUP BY` with Aggregate Functions
- Using `ORDER BY` with Grouped Results
- Using `DISTINCT` to Retrieve Unique Combinations
- Calculating Total Spending per Customer and Purchase Date
- Counting Purchases per Customer and Date
- Calculating Total Quantity Purchased per Customer and Date
- Counting Distinct Products Purchased
- Combining Multiple Aggregate Functions in One Query
- Calculating Spending Using Quantity and Cost per Unit
- Grouping Customer Spending by Purchase Date
- Understanding Buyer, Purchase, and Supplier Tables
- Introduction to SQL `JOIN`
- Using `LEFT JOIN` to Combine Tables
- Joining Buyers with Purchase Records
- Joining Purchase Records with Supplier Details
- Using Table Aliases in SQL Queries
- Referencing Columns from Multiple Joined Tables
- Understanding How Joins Create a Combined Dataset
- Generating Customer and Vendor Spending Reports
- Calculating Total Spending by Customer and Vendor
- Understanding the Purpose of the `HAVING` Clause
- Difference Between `WHERE` and `HAVING`
- Filtering Grouped Results Using Aggregate Conditions
- Using `COUNT()` and `SUM()` with `HAVING`
- Grouping Sales Data by Region
- Calculating Total Sales and Total Revenue by Region
- Filtering Regions by a Minimum Revenue Threshold
- Sorting Grouped Results by Total Revenue

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Relational-SQL/blob/main/dataretrievalandmanipulations.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Relational-SQL/raw/refs/heads/main/dataretrievalandmanipulations.pdf)

---

## Book References

Key resources used during my learning journey:

- *SQL for Data Scientists* by Renée M. P. Teate

---
## ⬅️⬅️ [Back to Main Profile](https://github.com/DhawaDG)
