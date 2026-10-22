Complete SQL Learning Roadmap
An 8-week, 56-day hands-on SQL learning plan using MySQL and MySQL Workbench.
Goal
Learn SQL one topic per day, practise each topic in MySQL Workbench, document the work,
solve additional questions, and publish consistent progress on GitHub.
Daily workflow
1. Learn the day's topic from a course or documentation.
2. Write and run the examples yourself in MySQL Workbench.
3. Save your queries in practice.sql.
4. Write explanations and takeaways in notes.md.
5. Put extra questions and solutions in questions.sql.
6. Save a screenshot of successful query results in screenshots/.
7. Review errors, fix them, then commit and push your work.
Suggested daily folder structure
Day-01-SQL-Basics/
├── notes.md
├── practice.sql
├── questions.sql
└── screenshots/
    └── results.png
Repeat this structure for each day, using a topic-specific folder name.
8-week roadmap
Week 1 — SQL Fundamentals
Day	Topic	What you'll learn / practical task
1	SQL and databases	SQL basics, databases, tables, rows, columns, and MySQL Workbench
2	Data types	INT, VARCHAR, DATE, DECIMAL, BOOLEAN
3	Database and table creation	CREATE DATABASE, CREATE TABLE, USE, DROP
4	Inserting data	INSERT INTO and inserting multiple rows
5	Retrieving data	SELECT, SELECT *, selecting specific columns, DISTINCT
6	Filtering data	WHERE, comparison operators, AND, OR, NOT
7	More filtering	IN, BETWEEN, LIKE, IS NULL, IS NOT NULL


Week 2 — Querying and Summarising Data
Day	Topic	What you'll learn / practical task
8	Sorting and limiting	ORDER BY, ASC, DESC, LIMIT
9	Updating and deleting	UPDATE, DELETE, and safe use of WHERE
10	Aggregate functions	COUNT, SUM, AVG, MIN, MAX
11	Grouping data	GROUP BY and grouping by multiple columns
12	Filtering groups	HAVING and WHERE vs HAVING
13	Conditional logic	CASE, IF, IFNULL, COALESCE
14	SQL revision	Mixed queries and a mini assessment


Week 3 — Relationships and Joins
Day	Topic	What you'll learn / practical task
15	Keys and constraints	Primary keys, foreign keys, UNIQUE, NOT NULL, DEFAULT, CHECK
16	Relationships	One-to-one, one-to-many, and many-to-many
17	INNER JOIN	Matching records between tables
18	LEFT JOIN	All left-table records and matching records
19	Other joins	RIGHT JOIN, cross joins, and self joins
20	Multi-table joins	Joining three or more tables
21	Join practice	Solve business-style questions using joins


Week 4 — Intermediate SQL
Day	Topic	What you'll learn / practical task
22	String functions	CONCAT, LENGTH, UPPER, LOWER, TRIM, SUBSTRING
23	Numeric functions	ROUND, ABS, CEIL, FLOOR, MOD
24	Date functions	CURDATE, DATEDIFF, DATE_ADD, YEAR, MONTH
25	Subqueries	Queries inside other queries
26	Subqueries with operators	EXISTS, NOT EXISTS, ANY, ALL
27	Set operations	UNION and UNION ALL
28	Revision	Combined filtering, grouping, functions, and joins


Week 5 — Advanced SQL
Day	Topic	What you'll learn / practical task
29	Altering tables	ALTER TABLE, add/modify/drop columns, rename columns
30	Views	CREATE VIEW, CREATE OR REPLACE VIEW, DROP VIEW
31	Common Table Expressions (CTEs)	WITH, multiple CTEs, and recursive CTE basics
32	Window functions	ROW_NUMBER, RANK, DENSE_RANK
33	Window calculations	OVER, PARTITION BY, LAG, LEAD
34	Indexes	CREATE INDEX, DROP INDEX, and index basics
35	Query execution	EXPLAIN and understanding query execution plans


Week 6 — Database Programming and Reliability
Day	Topic	What you'll learn / practical task
36	Transactions	START TRANSACTION, COMMIT, ROLLBACK
37	Savepoints	SAVEPOINT, ROLLBACK TO SAVEPOINT, RELEASE SAVEPOINT
38	Stored procedures	CREATE PROCEDURE, parameters, CALL
39	Stored functions	CREATE FUNCTION and return values
40	Control flow	IF, ELSEIF, CASE, and loops in stored programs
41	Triggers	CREATE TRIGGER, BEFORE, AFTER, INSERT, UPDATE, DELETE
42	Prepared statements	Parameters, PREPARE, EXECUTE, and SQL injection prevention concepts


Week 7 — Practical Projects and Interview Preparation
Day	Topic	What you'll learn / practical task
43	Database design	Design tables for a real-world application
44	Normalisation	Understand 1NF, 2NF, 3NF, and reduce duplication
45	Constraints and relationships	Build a relational database with valid relationships
46	E-commerce project	Customers, products, orders, and order items
47	Employee analytics project	Salaries, departments, rankings, and aggregations
48	Data analysis questions	Business questions using joins, CTEs, and window functions
49	Interview practice	Beginner, intermediate, and advanced SQL questions


Week 8 — Revision and Portfolio
Day	Topic	What you'll learn / practical task
50	Basic SQL revision	Solve 15 questions without notes
51	Filtering and functions	Solve 15 query problems
52	Joins and subqueries	Solve 15 relationship-based questions
53	Aggregation and window functions	Solve 15 analytical questions
54	Debugging SQL	Fix incorrect queries and explain the errors
55	Project completion	Finish one SQL project with a clean README
56	Mock interview	Attempt a timed SQL assessment and review mistakes


Learning rules
- Focus on understanding and practising one topic per day; do not rush through the roadmap.
- Use fictional sample data only. Never commit company data, passwords, tokens, or .env files.
- For commands such as DROP, DELETE, and UPDATE, practise only on your own learning database.
- Try questions before looking at solutions. Record mistakes and how you corrected them.
- Some syntax and behaviour vary across database systems; this roadmap targets MySQL.
Progress tracker
Use the checkboxes below to track each day. Tick a day only after practising and committing your work.
Week 1 — SQL Fundamentals
- [ ] Day 01 — SQL and databases
- [ ] Day 02 — Data types
- [ ] Day 03 — Database and table creation
- [ ] Day 04 — Inserting data
- [ ] Day 05 — Retrieving data
- [ ] Day 06 — Filtering data
- [ ] Day 07 — More filtering
Week 2 — Querying and Summarising Data
- [ ] Day 08 — Sorting and limiting
- [ ] Day 09 — Updating and deleting
- [ ] Day 10 — Aggregate functions
- [ ] Day 11 — Grouping data
- [ ] Day 12 — Filtering groups
- [ ] Day 13 — Conditional logic
- [ ] Day 14 — SQL revision
Week 3 — Relationships and Joins
- [ ] Day 15 — Keys and constraints
- [ ] Day 16 — Relationships
- [ ] Day 17 — INNER JOIN
- [ ] Day 18 — LEFT JOIN
- [ ] Day 19 — Other joins
- [ ] Day 20 — Multi-table joins
- [ ] Day 21 — Join practice
Week 4 — Intermediate SQL
- [ ] Day 22 — String functions
- [ ] Day 23 — Numeric functions
- [ ] Day 24 — Date functions
- [ ] Day 25 — Subqueries
- [ ] Day 26 — Subqueries with operators
- [ ] Day 27 — Set operations
- [ ] Day 28 — Revision
Week 5 — Advanced SQL
- [ ] Day 29 — Altering tables
- [ ] Day 30 — Views
- [ ] Day 31 — Common Table Expressions (CTEs)
- [ ] Day 32 — Window functions
- [ ] Day 33 — Window calculations
- [ ] Day 34 — Indexes
- [ ] Day 35 — Query execution
Week 6 — Database Programming and Reliability
- [ ] Day 36 — Transactions
- [ ] Day 37 — Savepoints
- [ ] Day 38 — Stored procedures
- [ ] Day 39 — Stored functions
- [ ] Day 40 — Control flow
- [ ] Day 41 — Triggers
- [ ] Day 42 — Prepared statements
Week 7 — Practical Projects and Interview Preparation
- [ ] Day 43 — Database design
- [ ] Day 44 — Normalisation
- [ ] Day 45 — Constraints and relationships
- [ ] Day 46 — E-commerce project
- [ ] Day 47 — Employee analytics project
- [ ] Day 48 — Data analysis questions
- [ ] Day 49 — Interview practice
Week 8 — Revision and Portfolio
- [ ] Day 50 — Basic SQL revision
- [ ] Day 51 — Filtering and functions
- [ ] Day 52 — Joins and subqueries
- [ ] Day 53 — Aggregation and window functions
- [ ] Day 54 — Debugging SQL
- [ ] Day 55 — Project completion
- [ ] Day 56 — Mock interview
Completion goal
By the end, aim to have a GitHub portfolio containing daily notes, executable SQL practice,
extra questions, screenshots, and at least one complete relational database project.

Important: This roadmap is a study plan, not a guarantee of job readiness. Build understanding through practice and be able to explain your query choices.