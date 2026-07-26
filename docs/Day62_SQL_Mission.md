
# 🌸 100 Days SQL Journey
## Day 62

## 🌼 Today's Topic
**CASE with Aggregate Functions**

**Goal:** Learn how to combine the `CASE` expression with aggregate functions to create meaningful business reports.

---

## 💖 A Little Message for Today
Every new concept builds on the last one. Keep practising with patience, and you'll soon be writing SQL queries that answer real business questions with confidence.

---

## 📚 Quick Revision
`CASE` can be used inside aggregate functions to count or summarize only specific records.

Example:
```sql
SELECT
    COUNT(CASE WHEN salary >= 60000 THEN 1 END) AS high_salary_count
FROM employees;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display the total number of employees with **High** and **Low** salary categories using `CASE`.

### Mission 2 (Easy)
Display the total number of products that are **Expensive** and **Affordable** using `CASE`.

### Mission 3 (Easy+)
Display the total ordered quantity separately for **Bulk Orders** and **Regular Orders** using `CASE`.

### Mission 4 (Medium)
Display each department with the number of employees whose salary is greater than 60000 using `CASE` and `GROUP BY`.

### Mission 5 (Challenge)
Display each product category with the number of **Low Stock** and **In Stock** products using `CASE`.

---

## 🏆 Bonus Challenge
Create a report showing each customer with the total number of **Large Orders** (based on quantity) using `CASE`.

---

## 💡 SQL Tip of the Day
`CASE` becomes even more powerful when combined with `SUM()`, `COUNT()`, and `GROUP BY` for creating custom reports.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll learn how to handle missing values using `NULL` and related SQL functions.

---

## 📝 Git Commit Message
`Completed Day 62 SQL Mission`

---

## 🎉 Closing Note
Fantastic work! You're learning how to turn raw data into meaningful insights. Keep practising, and each SQL concept will become a valuable tool in your toolkit.
