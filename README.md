
# Complete SQL Learning Roadmap

An 8-week, 56-day practical SQL learning plan using **MySQL** and **MySQL Workbench**.

## Goal

Learn one SQL topic per day, practise queries, document your learning, solve extra questions, and share your progress on GitHub.

## Daily Workflow

1. Learn the day's topic.
2. Practise the queries in MySQL Workbench.
3. Save your queries in `practice.sql`.
4. Write explanations in `notes.md`.
5. Solve extra questions in `questions.sql`.
6. Save screenshots in `screenshots/`.
7. Commit and push your work to GitHub.

## Folder Structure

```text
sql-practice/
├── README.md
├── complete_sql_learning_roadmap.pdf
├── Day-01-SQL-Basics/
│   ├── notes.md
│   ├── practice.sql
│   ├── questions.sql
│   └── screenshots/
├── Day-02-Data-Types/
│   ├── notes.md
│   ├── practice.sql
│   ├── questions.sql
│   └── screenshots/
└── ...
```

## Week 1 — SQL Fundamentals

| Day | Topic | What You'll Learn |
|---:|---|---|
| 1 | SQL and Databases | SQL basics, databases, tables, rows, columns, MySQL Workbench |
| 2 | Data Types | INT, VARCHAR, DATE, DECIMAL, BOOLEAN |
| 3 | Database and Table Creation | CREATE DATABASE, CREATE TABLE, USE, DROP |
| 4 | Inserting Data | INSERT INTO, inserting multiple rows |
| 5 | Retrieving Data | SELECT, SELECT *, DISTINCT, selecting columns |
| 6 | Filtering Data | WHERE, comparison operators, AND, OR, NOT |
| 7 | More Filtering | IN, BETWEEN, LIKE, IS NULL, IS NOT NULL |

## Week 2 — Querying and Summarising Data

| Day | Topic | What You'll Learn |
|---:|---|---|
| 8 | Sorting and Limiting | ORDER BY, ASC, DESC, LIMIT |
| 9 | Updating and Deleting | UPDATE, DELETE, safe use of WHERE |
| 10 | Aggregate Functions | COUNT, SUM, AVG, MIN, MAX |
| 11 | Grouping Data | GROUP BY, grouping by multiple columns |
| 12 | Filtering Groups | HAVING, WHERE vs HAVING |
| 13 | Conditional Logic | CASE, IF, IFNULL, COALESCE |
| 14 | SQL Revision | Mixed queries and mini assessment |

## Week 3 — Relationships and Joins

| Day | Topic | What You'll Learn |
|---:|---|---|
| 15 | Keys and Constraints | Primary keys, foreign keys, UNIQUE, NOT NULL, DEFAULT, CHECK |
| 16 | Relationships | One-to-one, one-to-many, many-to-many |
| 17 | INNER JOIN | Matching records between tables |
| 18 | LEFT JOIN | All left-table records and matching records |
| 19 | Other Joins | RIGHT JOIN, cross joins, self joins |
| 20 | Multi-table Joins | Joining three or more tables |
| 21 | Join Practice | Business-style questions using joins |

## Week 4 — Intermediate SQL

| Day | Topic | What You'll Learn |
|---:|---|---|
| 22 | String Functions | CONCAT, LENGTH, UPPER, LOWER, TRIM, SUBSTRING |
| 23 | Numeric Functions | ROUND, ABS, CEIL, FLOOR, MOD |
| 24 | Date Functions | CURDATE, DATEDIFF, DATE_ADD, YEAR, MONTH |
| 25 | Subqueries | Queries inside other queries |
| 26 | Subquery Operators | EXISTS, NOT EXISTS, ANY, ALL |
| 27 | Set Operations | UNION, UNION ALL |
| 28 | Revision | Filtering, grouping, functions, joins |

## Week 5 — Advanced SQL

| Day | Topic | What You'll Learn |
|---:|---|---|
| 29 | Altering Tables | ALTER TABLE, add, modify, drop, rename columns |
| 30 | Views | CREATE VIEW, CREATE OR REPLACE VIEW, DROP VIEW |
| 31 | Common Table Expressions | WITH, multiple CTEs, recursive CTE basics |
| 32 | Window Functions | ROW_NUMBER, RANK, DENSE_RANK |
| 33 | Window Calculations | OVER, PARTITION BY, LAG, LEAD |
| 34 | Indexes | CREATE INDEX, DROP INDEX, index basics |
| 35 | Query Execution | EXPLAIN, execution plans |

## Week 6 — Database Programming and Reliability

| Day | Topic | What You'll Learn |
|---:|---|---|
| 36 | Transactions | START TRANSACTION, COMMIT, ROLLBACK |
| 37 | Savepoints | SAVEPOINT, ROLLBACK TO SAVEPOINT, RELEASE SAVEPOINT |
| 38 | Stored Procedures | CREATE PROCEDURE, parameters, CALL |
| 39 | Stored Functions | CREATE FUNCTION, return values |
| 40 | Control Flow | IF, ELSEIF, CASE, loops in stored programs |
| 41 | Triggers | CREATE TRIGGER, BEFORE, AFTER, INSERT, UPDATE, DELETE |
| 42 | Prepared Statements | PREPARE, EXECUTE, parameters, SQL injection prevention |

## Week 7 — Projects and Interview Preparation

| Day | Topic | Practical Task |
|---:|---|---|
| 43 | Database Design | Design tables for a real-world application |
| 44 | Normalisation | Understand 1NF, 2NF, 3NF |
| 45 | Constraints and Relationships | Build a relational database |
| 46 | E-commerce Project | Customers, products, orders, order items |
| 47 | Employee Analytics Project | Salaries, departments, rankings, aggregations |
| 48 | Data Analysis Questions | Business problems using joins, CTEs, window functions |
| 49 | Interview Practice | Beginner, intermediate, advanced SQL questions |

## Week 8 — Revision and Portfolio

| Day | Topic | Practical Task |
|---:|---|---|
| 50 | Basic SQL Revision | Solve 15 questions without notes |
| 51 | Filtering and Functions | Solve 15 query problems |
| 52 | Joins and Subqueries | Solve 15 relationship-based questions |
| 53 | Aggregation and Window Functions | Solve 15 analytical questions |
| 54 | Debugging SQL | Fix incorrect queries and explain errors |
| 55 | Project Completion | Finish a SQL project with a clean README |
| 56 | Mock Interview | Complete a timed SQL assessment |

## GitHub Commit Workflow

After completing each day's work, run:

```bash
git add Day-01-SQL-Basics
git commit -m "Complete Day 01 SQL basics"
git push
```

Update the folder name and commit message for each new day.

## Learning Rules

- Focus on understanding one topic per day.
- Practise every query yourself before checking solutions.
- Record mistakes and how you fixed them.
- Use fictional data only.
- Never commit passwords, tokens, `.env` files, or private company data.
- Practise UPDATE, DELETE, and DROP only in your own learning database.

## Completion Goal

Build a GitHub portfolio with daily notes, SQL practice, extra questions, screenshots, and at least one complete relational database project.

**Consistency matters more than speed.** The goal is to understand SQL well enough to write queries independently and explain your approach.
