
# 🌸 100 Days SQL Journey
## Day 89

## 🌼 Today's Topic
**Composite Indexes – Multi-Column Indexing**

**Goal:** Learn how composite indexes work, when to create them, and how they differ from single-column indexes.

---

## 💖 A Little Message for Today

Choosing the right index is just as important as writing the right query. Composite indexes help optimise queries that filter or sort using multiple columns together.

---

## 📚 Quick Revision

A **composite index** is an index built on two or more columns.

Example:

```sql
CREATE INDEX idx_emp_dept_salary
ON employees(department_id, salary);
```

This index is useful for queries such as:

```sql
SELECT *
FROM employees
WHERE department_id = 2
ORDER BY salary DESC;
```

The order of columns in a composite index matters.

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Create a composite index on `employees(department_id, salary)`.

### Mission 2 (Easy)
Create a composite index on `orders(customer_id, order_date)`.

### Mission 3 (Easy+)
Write a query that filters employees by `department_id` and sorts by `salary`.

### Mission 4 (Medium)
Write a query that filters orders by `customer_id` and sorts them by `order_date`.

### Mission 5 (Challenge)
Compare a single-column index with a composite index for a query that filters on one column and sorts on another. Explain which index is more suitable and why.

---

## 🏆 Bonus Challenge

Create a composite index on `products(category, price)`. Write a query that filters by `category` and displays products ordered by `price`, then discuss how the index can improve performance.

---

## 💡 SQL Tip of the Day

Create composite indexes based on the columns that are commonly used together in `WHERE`, `JOIN`, and `ORDER BY` clauses. Avoid creating unnecessary indexes because they increase storage and maintenance costs.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to analyse query performance using `EXPLAIN` (or `EXPLAIN QUERY PLAN` in SQLite).

---

## 📝 Git Commit Message

`Completed Day 89 SQL Mission`

---

## 🎉 Closing Note

Excellent work! You're now learning how databases optimise complex queries. Understanding composite indexes will help you design faster and more efficient SQL applications.
