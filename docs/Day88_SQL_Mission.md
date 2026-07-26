
# 🌸 100 Days SQL Journey
## Day 88

## 🌼 Today's Topic
**SQL Indexes – Introduction**

**Goal:** Learn what SQL indexes are, why they are used, and how they improve query performance.

---

## 💖 A Little Message for Today

As databases grow larger, queries can become slower. Indexes help the database find data more efficiently, making searches and reports much faster.

---

## 📚 Quick Revision

An **index** is a database object that speeds up data retrieval.

Create an index:

```sql
CREATE INDEX idx_employee_last_name
ON employees(last_name);
```

View data normally:

```sql
SELECT *
FROM employees
WHERE last_name = 'Sharma';
```

> The database can use the index to locate matching rows more quickly.

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Create an index on the `last_name` column of the `employees` table.

### Mission 2 (Easy)
Create an index on the `city` column of the `customers` table.

### Mission 3 (Easy+)
Create an index on the `category` column of the `products` table.

### Mission 4 (Medium)
Run a query that searches employees by `last_name` and observe how the index is intended to improve lookups.

### Mission 5 (Challenge)
Create indexes on the foreign key columns `customer_id` and `product_id` in the `orders` table, then use those columns in filtering or join queries.

---

## 🏆 Bonus Challenge

Create a composite index on `(department_id, salary)` in the `employees` table. Write a query that filters by `department_id` and sorts by `salary`, then discuss why a composite index can be helpful.

---

## 💡 SQL Tip of the Day

Indexes speed up `SELECT` queries but can slightly slow down `INSERT`, `UPDATE`, and `DELETE` operations because the index must also be maintained.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn about composite indexes and discover when to use single-column versus multi-column indexes.

---

## 📝 Git Commit Message

`Completed Day 88 SQL Mission`

---

## 🎉 Closing Note

Fantastic progress! Understanding indexes is a key step toward writing efficient SQL and building high-performance databases. Keep practising, and you'll soon appreciate how much difference good indexing makes.
