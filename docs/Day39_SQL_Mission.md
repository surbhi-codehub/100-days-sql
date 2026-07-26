
# 🌸 100 Days SQL Journey
## Day 39

## 🌼 Today's Topic
**Practice with Aggregate Functions**

**Goal:** Strengthen your understanding of `COUNT()`, `SUM()`, `AVG()`, `MIN()`, and `MAX()` by solving practical business-style problems.

---

## 💖 A Little Message for Today
Confidence comes from repetition. The more you practise, the more naturally SQL will come to you. Keep showing up—your future self will thank you.

---

## 📚 Quick Revision
Aggregate functions summarize data into meaningful values.

Common functions:
- `COUNT()` → Number of rows
- `SUM()` → Total
- `AVG()` → Average
- `MIN()` → Smallest value
- `MAX()` → Largest value

Example:
```sql
SELECT COUNT(*), AVG(salary), MAX(salary)
FROM employees;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display the total number of products and the average product price.

### Mission 2 (Easy)
Find the total quantity ordered and the maximum quantity ordered from the `orders` table.

### Mission 3 (Easy+)
Display the minimum, maximum, and average salary of all employees.

### Mission 4 (Medium)
For products in the **Electronics** category, display the total number of products, total stock quantity, and average product price.

### Mission 5 (Challenge)
For employees whose `department_id` is 1, display the total employees, total salary, average salary, minimum salary, and maximum salary in a single query.

---

## 🏆 Bonus Challenge
Write one query to display the total number of orders together with the minimum, maximum, and average order quantity.

---

## 💡 SQL Tip of the Day
Aggregate functions return a single summary row unless you later combine them with `GROUP BY`.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll begin exploring the `GROUP BY` clause to summarize data by categories.

---

## 📝 Git Commit Message
`Completed Day 39 SQL Mission`

---

## 🎉 Closing Note
You've built a solid foundation with aggregate functions. Keep practising these patterns—they're used in almost every real-world SQL project.
