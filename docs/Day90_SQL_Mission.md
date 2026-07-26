
# 🌸 100 Days SQL Journey
## Day 90

## 🌼 Today's Topic
**EXPLAIN & EXPLAIN QUERY PLAN – Understanding Query Performance**

**Goal:** Learn how to analyse SQL queries using `EXPLAIN` (or `EXPLAIN QUERY PLAN` in SQLite) to understand how the database executes a query.

---

## 💖 A Little Message for Today

Writing a correct query is only half the job. Professional SQL developers also check how efficiently the database executes it. Today you'll learn to look behind the scenes.

---

## 📚 Quick Revision

`EXPLAIN` shows how the database plans to execute a query.

SQLite example:

```sql
EXPLAIN QUERY PLAN
SELECT *
FROM employees
WHERE department_id = 2;
```

Many other databases support:

```sql
EXPLAIN
SELECT *
FROM employees
WHERE department_id = 2;
```

Use it before and after creating indexes to observe how query execution changes.

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Run `EXPLAIN QUERY PLAN` for a query that selects all employees.

### Mission 2 (Easy)
Run `EXPLAIN QUERY PLAN` for a query filtering employees by `department_id`.

### Mission 3 (Easy+)
Create an index on `department_id` (if one doesn't exist) and compare the execution plan before and after creating the index.

### Mission 4 (Medium)
Analyse the execution plan of a query that joins `orders` and `customers`.

### Mission 5 (Challenge)
Analyse the execution plan of a query that filters products by `category` and sorts them by `price`. Explain whether an index could improve performance.

---

## 🏆 Bonus Challenge

Compare the execution plans for:
- A query without an index.
- The same query after creating an appropriate index.

Identify whether the database performs a full table scan or uses an index.

---

## 💡 SQL Tip of the Day

`EXPLAIN` helps you understand *how* SQL executes a query. It's one of the best tools for diagnosing slow queries and validating your indexing strategy.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll begin learning SQL transactions, including `BEGIN`, `COMMIT`, and `ROLLBACK`.

---

## 📝 Git Commit Message

`Completed Day 90 SQL Mission`

---

## 🎉 Closing Note

Congratulations on reaching Day 90! You're now exploring SQL performance tuning—an important skill for every Data Engineer and Database Developer. Keep experimenting with execution plans, and you'll learn to write SQL that's both correct and efficient.
