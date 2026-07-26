
# 🌸 100 Days SQL Journey
## Day 77

## 🌼 Today's Topic
**DISTINCT – Retrieving Unique Values**

**Goal:** Learn how to eliminate duplicate values from query results using the `DISTINCT` keyword.

---

## 💖 A Little Message for Today
Databases often contain repeated values, especially in columns like cities, departments, and categories. `DISTINCT` helps you focus on unique information and build cleaner reports.

---

## 📚 Quick Revision

- `DISTINCT` returns only unique values.
- It can be used with one or more columns.
- Duplicate rows are removed from the result.

Example:

```sql
SELECT DISTINCT city
FROM customers;
```

You can also use:

```sql
SELECT DISTINCT category
FROM products;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display all unique cities from the `customers` table.

### Mission 2 (Easy)
Display all unique job titles from the `employees` table.

### Mission 3 (Easy+)
Display all unique product categories from the `products` table.

### Mission 4 (Medium)
Display all unique combinations of `city` and `department_id` from the `employees` table.

### Mission 5 (Challenge)
Create a report showing all unique customer cities sorted alphabetically.

---

## 🏆 Bonus Challenge

Write two queries:
1. Display all cities from the `customers` table.
2. Display only unique cities using `DISTINCT`.

Compare the number of rows returned and explain the difference.

---

## 💡 SQL Tip of the Day

`DISTINCT` removes duplicate rows from the selected columns only. Combining it with `ORDER BY` makes unique results easier to read.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to calculate totals and summaries using aggregate functions together with `DISTINCT`.

---

## 📝 Git Commit Message

`Completed Day 77 SQL Mission`

---

## 🎉 Closing Note

Excellent work! Understanding `DISTINCT` is an important step toward creating accurate reports and analysing data efficiently. Keep practising, and you'll soon know exactly when to use it.
