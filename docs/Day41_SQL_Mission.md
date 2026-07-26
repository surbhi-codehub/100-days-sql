
# 🌸 100 Days SQL Journey
## Day 41

## 🌼 Today's Topic
**GROUP BY – Introduction**

**Goal:** Learn how to group rows with the same value and calculate summaries for each group.

---

## 💖 A Little Message for Today
You're entering one of the most useful parts of SQL. Take it one query at a time, and don't worry if it feels new. Practice will turn today's challenge into tomorrow's strength.

---

## 📚 Quick Revision
`GROUP BY` combines rows that have the same value in a column.
It is commonly used with aggregate functions like `COUNT()`, `SUM()`, `AVG()`, `MIN()`, and `MAX()`.

Example:
```sql
SELECT department_id, COUNT(*)
FROM employees
GROUP BY department_id;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display the number of employees in each `department_id`.

### Mission 2 (Easy)
Display the number of products in each product category.

### Mission 3 (Easy+)
Display the total stock quantity for each product category.

### Mission 4 (Medium)
Display the average salary for each `department_id`.

### Mission 5 (Challenge)
Display the total number of orders and the total ordered quantity for each customer.

---

## 🏆 Bonus Challenge
Display the minimum and maximum product price for each product category.

---

## 💡 SQL Tip of the Day
Every column in the `SELECT` list must either be included in `GROUP BY` or be used inside an aggregate function.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll practise `GROUP BY` with multiple aggregate functions.

---

## 📝 Git Commit Message
`Completed Day 41 SQL Mission`

---

## 🎉 Closing Note
Fantastic work reaching Day 41! You're now learning how to summarise data like a real data analyst. Keep practising, and each query will become more natural.
