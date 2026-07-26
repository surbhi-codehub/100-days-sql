
# 🌸 100 Days SQL Journey
## Day 38

## 🌼 Today's Topic
**Using Multiple Aggregate Functions Together**

**Goal:** Learn how to use `COUNT()`, `SUM()`, `AVG()`, `MIN()`, and `MAX()` in a single query to get a quick summary of your data.

---

## 💖 A Little Message for Today
Every concept you learn becomes a building block for something bigger. Trust the process, keep practising, and let your confidence grow one query at a time.

---

## 📚 Quick Revision
Aggregate functions help summarize data.
You can use multiple aggregate functions in one `SELECT` statement.

Example:
```sql
SELECT COUNT(*), SUM(quantity), AVG(quantity), MIN(quantity), MAX(quantity)
FROM orders;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display the total number of employees and the minimum and maximum salary.

### Mission 2 (Easy)
Show the total number of products along with the minimum and maximum product price.

### Mission 3 (Easy+)
Display the total number of orders, total ordered quantity, and average order quantity.

### Mission 4 (Medium)
For products in the **Electronics** category, display the total number of products, minimum price, maximum price, and average price.

### Mission 5 (Challenge)
For employees in `department_id = 2`, display the total number of employees, total salary, average salary, minimum salary, and maximum salary.

---

## 🏆 Bonus Challenge
Create a single query that shows the total number of customers and the earliest and latest registration date (or customer creation date if available).

---

## 💡 SQL Tip of the Day
Using several aggregate functions in one query is often faster and cleaner than writing multiple separate queries.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll start grouping data with the powerful `GROUP BY` clause.

---

## 📝 Git Commit Message
`Completed Day 38 SQL Mission`

---

## 🎉 Closing Note
You've completed the aggregate functions section! Keep practising these functions—they'll be used in real-world SQL every day.
