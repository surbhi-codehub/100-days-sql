
# 🌸 100 Days SQL Journey
## Day 48

## 🌼 Today's Topic
**INNER JOIN – Introduction**

**Goal:** Learn how to combine related data from two tables using `INNER JOIN`.

---

## 💖 A Little Message for Today
You've built a strong foundation with filtering and grouping. Today you'll unlock one of the most powerful SQL features—joining tables. Take it slowly, and enjoy connecting the pieces together.

---

## 📚 Quick Revision
`INNER JOIN` returns only the rows that have matching values in both tables.

Example:
```sql
SELECT e.employee_name,
       d.department_name
FROM employees e
INNER JOIN departments d
ON e.department_id = d.department_id;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display each employee along with the name of their department.

### Mission 2 (Easy)
Display each order along with the customer name.

### Mission 3 (Easy+)
Display each product together with its supplier name.

### Mission 4 (Medium)
Display each order with the customer name and the product name.

### Mission 5 (Challenge)
Display each employee, their department name, and the department location (if available in the uploaded database).

---

## 🏆 Bonus Challenge
Display each customer along with the total number of orders they have placed by combining `INNER JOIN` and `COUNT()`.

---

## 💡 SQL Tip of the Day
Always join tables using their related primary key and foreign key columns to avoid incorrect results.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll practise `INNER JOIN` with multiple tables and aggregate functions.

---

## 📝 Git Commit Message
`Completed Day 48 SQL Mission`

---

## 🎉 Closing Note
Congratulations on starting SQL joins! This is where databases truly come alive. Keep practising, and you'll soon be writing queries that connect data like a professional.
