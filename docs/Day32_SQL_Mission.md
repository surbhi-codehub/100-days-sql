# 🌸 100 Days SQL Journey

# ✨ Day 32

## 🌼 Today's Topic
**COUNT() with Conditions**

**Goal:** Learn how to count only the rows that match a condition using `WHERE`.

---

## 💖 A Little Message for Today

Every small query you write makes you a stronger problem solver.  
Keep building one skill at a time—your consistency is your biggest advantage. 🌱

---

## 📚 Quick Revision

`COUNT()` counts rows.  
When combined with `WHERE`, it counts only matching records.

Example:

```sql
SELECT COUNT(*) FROM employees
WHERE city = 'Mumbai';
```

This returns the number of employees from Mumbai.

---

## 🎯 Today's SQL Missions

### Mission 1 ⭐
Count how many employees belong to the **Sales** department (`department_id = 1`).

### Mission 2 ⭐⭐
Count how many products have a price greater than 100.

### Mission 3 ⭐⭐⭐
Count how many customers live in **Delhi**.

### Mission 4 ⭐⭐⭐⭐
Count the number of orders where the quantity is greater than 3.

### Mission 5 🚀 Challenge
Count how many employees earn a salary greater than 60000 and belong to department 2.

---

## 🏆 Bonus Challenge

How many products have stock quantity below 20?

---

## 💡 SQL Tip of the Day

Use `COUNT(*)` when you want to count rows regardless of column values.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to calculate totals using **SUM()**.

---

## 📝 Git Commit Message

`Completed Day 32 SQL Mission`

---

## 🎉 Closing Note

You completed another step in your SQL journey.  
Keep practicing every day—confidence grows through repetition. 🌟
