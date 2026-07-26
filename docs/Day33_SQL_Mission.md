
# 🌸 100 Days SQL Journey
## Day 33

### 🌼 Today's Topic
**COUNT() with WHERE**

**Goal:** Learn how to count only the rows that match a condition.

---

### 💖 A Little Message for Today
Every small query you write strengthens your SQL skills. Keep practising consistently, and today's effort will make tomorrow's challenges much easier.

---

### 📚 Quick Revision
`COUNT()` returns the number of rows.
You can combine it with `WHERE` to count only matching records.

Example:
```sql
SELECT COUNT(*)
FROM orders
WHERE quantity >= 5;
```

---

## 🎯 Today's SQL Missions

**Mission 1 (Very Easy)**  
Count the total number of customers.

**Mission 2 (Easy)**  
Count how many products belong to the **Electronics** category.

**Mission 3 (Easy+)**  
Count how many employees work in the **Sales** department using the `department_id`.

**Mission 4 (Medium)**  
Count the number of orders placed where the quantity is greater than 3.

**Mission 5 (Challenge)**  
Count how many employees earn a salary greater than 60000.

---

### 🏆 Bonus Challenge
How many customers are from the same city as at least one employee? (Count customers only.)

---

### 💡 SQL Tip of the Day
Use `COUNT(*)` when you want to count rows regardless of column values.

---

### 🌱 Tomorrow's Preview
Tomorrow you'll discover how to calculate totals using `SUM()`.

---

### 📝 Git Commit Message
`Completed Day 33 SQL Mission`

---

### 🎉 Closing Note
Consistency beats perfection. Keep writing queries, stay curious, and enjoy the journey one day at a time.
