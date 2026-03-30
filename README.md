# 🗄️ Oracle SQL & PL/SQL — Learning Repository

<div align="center">

![Oracle](https://img.shields.io/badge/Oracle-Database-F80000?style=flat-square&logo=oracle&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Structured%20Query%20Language-003B57?style=flat-square)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-Procedural%20Language-336791?style=flat-square)
![Level](https://img.shields.io/badge/Level-Beginner%20Friendly-22c55e?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-f59e0b?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active%20Learning-6366f1?style=flat-square)

**A structured, beginner-friendly space to learn, practice, and master Oracle SQL & PL/SQL.**  
*Organized by topic. Thoroughly commented. Built for real understanding.*

[📚 Topics](#-topics-covered) · [🚀 Getting Started](#-getting-started) · [📁 Structure](#-repository-structure) · [🧪 Exercises](#-practice-exercises) · [📖 Resources](#-resources)

</div>

---

## 🎯 About This Repository

This repository is a personal **learning and practice workspace** for Oracle SQL and PL/SQL. Every file is:

- ✅ **Commented** — each concept is explained inline
- ✅ **Organized** — numbered folders in logical learning order
- ✅ **Beginner-safe** — no assumed prior knowledge within each topic
- ✅ **Runnable** — all scripts tested against Oracle XE / Oracle 21c

> Whether you're preparing for an **Oracle Certification**, working on a **real project**, or simply building your database skills — this repo grows with you.

---

## 📁 Repository Structure

```
oracle-sql-plsql/
│
├── 📂 01_SQL_Queries/
│   ├── 01_select_basics.sql          -- SELECT, FROM, aliases, DISTINCT
│   ├── 02_where_filtering.sql        -- WHERE, AND, OR, IN, BETWEEN, LIKE
│   ├── 03_joins.sql                  -- INNER, LEFT, RIGHT, FULL OUTER, SELF
│   ├── 04_aggregations.sql           -- GROUP BY, HAVING, COUNT, SUM, AVG
│   ├── 05_subqueries.sql             -- Nested & correlated subqueries
│   ├── 06_set_operations.sql         -- UNION, INTERSECT, MINUS
│   ├── 07_window_functions.sql       -- ROW_NUMBER, RANK, LAG, LEAD
│   └── README.md
│
├── 📂 02_PLSQL_Basics/
│   ├── 01_anonymous_blocks.sql       -- DECLARE / BEGIN / EXCEPTION / END
│   ├── 02_variables_datatypes.sql    -- VARCHAR2, NUMBER, DATE, %TYPE
│   ├── 03_control_flow.sql           -- IF/ELSIF, CASE, LOOP, FOR, WHILE
│   ├── 04_cursors.sql                -- Implicit, explicit, cursor FOR loop
│   ├── 05_exception_handling.sql     -- NO_DATA_FOUND, WHEN OTHERS, user-defined
│   └── README.md
│
├── 📂 03_Procedures_Functions/
│   ├── 01_stored_procedures.sql      -- CREATE PROCEDURE, IN/OUT/IN OUT params
│   ├── 02_functions.sql              -- CREATE FUNCTION, RETURN, deterministic
│   ├── 03_parameter_modes.sql        -- IN, OUT, IN OUT with examples
│   ├── 04_overloading.sql            -- Multiple signatures inside packages
│   └── README.md
│
├── 📂 04_Triggers_Packages/
│   ├── 01_row_triggers.sql           -- BEFORE/AFTER INSERT, UPDATE, DELETE
│   ├── 02_statement_triggers.sql     -- Table-level event triggers
│   ├── 03_instead_of_triggers.sql    -- Triggers on views
│   ├── 04_compound_triggers.sql      -- Multi-timing compound triggers
│   ├── 05_package_spec.sql           -- Package specification (public interface)
│   ├── 06_package_body.sql           -- Package body (implementation)
│   └── README.md
│
├── 📂 05_Performance_Tuning/
│   ├── 01_explain_plan.sql           -- EXPLAIN PLAN, DBMS_XPLAN.DISPLAY
│   ├── 02_indexes.sql                -- B-Tree, Bitmap, Function-based, Composite
│   ├── 03_optimizer_hints.sql        -- /*+ FULL */ /*+ INDEX */ /*+ PARALLEL */
│   ├── 04_query_optimization.sql     -- Avoid SELECT *, bind variables, joins
│   ├── 05_partitioning_basics.sql    -- Range, list, hash partitioning overview
│   └── README.md
│
├── 📂 06_Sample_Schemas/
│   ├── hr_schema_setup.sql           -- HR schema (employees, departments, jobs)
│   ├── sales_schema_setup.sql        -- Custom sales schema for practice
│   └── seed_data.sql                 -- Sample data inserts
│
├── 📂 07_Practice_Exercises/
│   ├── level1_basic.sql              -- SELECT, filter, sort challenges
│   ├── level2_intermediate.sql       -- JOINs, aggregations, subqueries
│   ├── level3_advanced.sql           -- PL/SQL, triggers, performance
│   └── solutions/
│       ├── level1_solutions.sql
│       ├── level2_solutions.sql
│       └── level3_solutions.sql
│
├── .gitignore
├── CONTRIBUTING.md
├── CHANGELOG.md
└── README.md
```

---

## 🧠 Topics Covered

### 📌 Module 1 — SQL Queries

| # | Topic | Key Concepts |
|---|-------|-------------|
| 01 | SELECT Basics | `SELECT`, `FROM`, `WHERE`, column aliases, `DISTINCT` |
| 02 | Filtering Data | `AND`, `OR`, `NOT`, `IN`, `BETWEEN`, `LIKE`, `IS NULL` |
| 03 | Joins | `INNER JOIN`, `LEFT/RIGHT OUTER`, `FULL OUTER`, `SELF JOIN` |
| 04 | Aggregations | `GROUP BY`, `HAVING`, `COUNT`, `SUM`, `AVG`, `MIN`, `MAX` |
| 05 | Subqueries | Inline views, correlated subqueries, `EXISTS`, `NOT EXISTS` |
| 06 | Set Operations | `UNION`, `UNION ALL`, `INTERSECT`, `MINUS` |
| 07 | Window Functions | `ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`, `LAG()`, `LEAD()` |

### 📌 Module 2 — PL/SQL Basics

| # | Topic | Key Concepts |
|---|-------|-------------|
| 01 | Anonymous Blocks | `DECLARE`, `BEGIN`, `EXCEPTION`, `END` structure |
| 02 | Variables & Types | `VARCHAR2`, `NUMBER`, `DATE`, `%TYPE`, `%ROWTYPE` |
| 03 | Control Flow | `IF/ELSIF/ELSE`, `CASE`, `LOOP`, `WHILE`, `FOR` |
| 04 | Cursors | Implicit cursors, explicit cursors, cursor `FOR` loops |
| 05 | Exception Handling | Built-in exceptions, `WHEN OTHERS`, user-defined exceptions |

### 📌 Module 3 — Procedures & Functions

| # | Topic | Key Concepts |
|---|-------|-------------|
| 01 | Stored Procedures | `CREATE OR REPLACE PROCEDURE`, `EXEC`, `CALL` |
| 02 | Functions | `CREATE OR REPLACE FUNCTION`, `RETURN`, deterministic |
| 03 | Parameter Modes | `IN`, `OUT`, `IN OUT` parameter types |
| 04 | Overloading | Multiple signatures within packages |

### 📌 Module 4 — Triggers & Packages

| # | Topic | Key Concepts |
|---|-------|-------------|
| 01 | Row-Level Triggers | `:NEW`, `:OLD`, `FOR EACH ROW` |
| 02 | Statement Triggers | Table-level triggers without row binding |
| 03 | INSTEAD OF Triggers | Triggers on views for DML operations |
| 04 | Compound Triggers | Multi-timing triggers, mutating table solution |
| 05 | Package Spec | Public variables, procedures, function signatures |
| 06 | Package Body | Private logic, implementation, initialization |

### 📌 Module 5 — Performance Tuning

| # | Topic | Key Concepts |
|---|-------|-------------|
| 01 | Explain Plan | `EXPLAIN PLAN FOR`, `DBMS_XPLAN.DISPLAY`, cost analysis |
| 02 | Indexes | B-Tree, Bitmap, Function-based, Composite indexes |
| 03 | Optimizer Hints | `/*+ FULL */`, `/*+ INDEX */`, `/*+ USE_NL */` |
| 04 | Query Optimization | Avoid `SELECT *`, use bind variables, proper joins |
| 05 | Partitioning | Range, list, hash partitioning overview |

---

## 🚀 Getting Started

### Prerequisites

| Tool | Purpose | Link |
|------|---------|------|
| Oracle Database XE | Free Oracle database engine | [Download](https://www.oracle.com/database/technologies/xe-downloads.html) |
| SQL Developer | GUI IDE for Oracle | [Download](https://www.oracle.com/tools/downloads/sqldev-downloads.html) |
| Oracle Live SQL | Browser-based sandbox | [Use Online](https://livesql.oracle.com) |

> **No installation?** Use [Oracle Live SQL](https://livesql.oracle.com) — free, browser-based, no setup needed.

---

### Step-by-Step Setup

**1. Clone the repository**

```bash
git clone https://github.com/your-username/oracle-sql-plsql.git
cd oracle-sql-plsql
```

**2. Connect to Oracle Database**

```bash
# Using SQL*Plus
sqlplus username/password@localhost:1521/XEPDB1
```

Or open SQL Developer and create a connection:
- Host: `localhost` | Port: `1521` | SID: `XE`

**3. Set up the sample schema**

```sql
-- Run the HR schema (required for most examples)
@06_Sample_Schemas/hr_schema_setup.sql

-- Load practice data
@06_Sample_Schemas/seed_data.sql
```

**4. Start with Module 1**

```sql
@01_SQL_Queries/01_select_basics.sql
```

---

## 🧪 Practice Exercises

Three tiers of challenges in `07_Practice_Exercises/`:

| Level | File | Focus Area |
|-------|------|-----------|
| ⭐ Beginner | `level1_basic.sql` | SELECT, filters, sorting, simple joins |
| ⭐⭐ Intermediate | `level2_intermediate.sql` | Complex joins, aggregations, subqueries |
| ⭐⭐⭐ Advanced | `level3_advanced.sql` | PL/SQL blocks, packages, performance |

> 💡 Always attempt the exercises first — solutions are in the `solutions/` subfolder.

---

## 📖 Resources

| Resource | Description |
|----------|-------------|
| [Oracle Docs](https://docs.oracle.com/en/database/) | Official reference for all Oracle Database features |
| [Oracle Live SQL](https://livesql.oracle.com) | Write and run SQL directly in your browser |
| [Oracle Dev Gym](https://devgym.oracle.com) | Free quizzes, workouts, and guided courses |
| [Ask TOM](https://asktom.oracle.com) | Expert answers to real Oracle questions |
| [Oracle Tutorial](https://www.oracletutorial.com) | Beginner-friendly tutorials with examples |
| [Use The Index, Luke](https://use-the-index-luke.com) | Deep dive into SQL indexing and performance |

---

## 🤝 Contributing

Pull requests, fixes, and new examples are welcome!

```bash
# Fork → Branch → Commit → Push → Pull Request

git checkout -b feature/add-analytic-functions
git commit -m "feat: add analytic window function examples"
git push origin feature/add-analytic-functions
```

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting.

---

## 📄 License

Licensed under the [MIT License](LICENSE).

---

<div align="center">

Made with ❤️ for Oracle learners everywhere.

⭐ **Star this repo** if it helped you — it motivates more content!

</div>
