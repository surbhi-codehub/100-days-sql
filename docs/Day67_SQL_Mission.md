
# 🌸 100 Days SQL Journey
## Day 67

## 🌼 Today's Topic
**UNION ALL**

**Goal:** Learn how to combine the results of multiple `SELECT` queries while keeping duplicate rows.

---

## 💖 A Little Message for Today
Every SQL feature has its own purpose. Understanding when to use `UNION` and when to use `UNION ALL` will help you write faster and more accurate queries. Keep exploring!

---

## 📚 Quick Revision
`UNION ALL` combines the results of two or more `SELECT` statements.
Unlike `UNION`, it **does not remove duplicate rows**, making it faster in many cases.

Example:
```sql
SELECT customer_name
FROM customers

UNION ALL

SELECT supplier_name
FROM suppliers;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Combine names from two tables using `UNION ALL`.

### Mission 2 (Easy)
Combine IDs from two related tables using `UNION ALL`.

### Mission 3 (Easy+)
Display employee names and customer names in one result, allowing duplicate names.

### Mission 4 (Medium)
Combine product categories from two queries using `UNION ALL` and compare the output with `UNION`.

### Mission 5 (Challenge)
Create a report by combining records from two tables with matching column structures using `UNION ALL`.

---

## 🏆 Bonus Challenge
Create two queries—one using `UNION` and one using `UNION ALL`—and observe how duplicate rows affect the results.

---

## 💡 SQL Tip of the Day
Use `UNION ALL` when duplicate rows are meaningful or when you want better performance by avoiding duplicate removal.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll practise `UNION` and `UNION ALL` together using practical business scenarios.

---

## 📝 Git Commit Message
`Completed Day 67 SQL Mission`

---

## 🎉 Closing Note
You're expanding your SQL toolkit with another powerful operator. Keep practising, compare the results carefully, and your understanding will grow with every query.
