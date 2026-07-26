
# 🌸 100 Days SQL Journey
## Day 68

## 🌼 Today's Topic
**UNION vs UNION ALL – Practical Comparison**

**Goal:** Understand the difference between `UNION` and `UNION ALL` and know when to use each.

---

## 💖 A Little Message for Today
You're learning not just SQL syntax, but also how to choose the right tool for the job. Comparing similar features is one of the best ways to deepen your understanding.

---

## 📚 Quick Revision

- `UNION` combines results and removes duplicate rows.
- `UNION ALL` combines results and keeps duplicate rows.
- Both queries must return the same number of columns with compatible data types.

Example:

```sql
SELECT city FROM customers
UNION
SELECT city FROM employees;
```

```sql
SELECT city FROM customers
UNION ALL
SELECT city FROM employees;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Combine city names from `customers` and `employees` using `UNION`.

### Mission 2 (Easy)
Run the same query using `UNION ALL` and compare the number of rows returned.

### Mission 3 (Easy+)
Combine first names from `customers` and `employees` using both operators and observe the difference.

### Mission 4 (Medium)
Create two reports—one with `UNION` and one with `UNION ALL`—for product categories selected using different conditions.

### Mission 5 (Challenge)
Build a report that combines data from multiple queries and explain why `UNION` or `UNION ALL` is the better choice.

---

## 🏆 Bonus Challenge

Write one query using `UNION` and another using `UNION ALL`. Compare the execution results and explain which operator is more appropriate for reporting and which is better when every row must be preserved.

---

## 💡 SQL Tip of the Day

Choose `UNION` when duplicate rows should be removed. Choose `UNION ALL` when every row matters or when better performance is important.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll begin learning SQL string functions for working with text data.

---

## 📝 Git Commit Message

`Completed Day 68 SQL Mission`

---

## 🎉 Closing Note

Excellent work! Understanding the differences between similar SQL features helps you write more efficient and accurate queries. Keep building your confidence one day at a time.
