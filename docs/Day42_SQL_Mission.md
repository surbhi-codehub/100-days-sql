
# 🌸 100 Days SQL Journey
## Day 42

## 🌼 Today's Topic
**GROUP BY with Multiple Aggregate Functions**

**Goal:** Learn how to use `GROUP BY` together with several aggregate functions to create meaningful summaries for each group.

---

## 💖 A Little Message for Today
Every new concept opens the door to solving bigger problems. Keep exploring with patience, and remember that steady practice always beats rushing.

---

## 📚 Quick Revision
`GROUP BY` creates one result for each unique value in a column.
You can calculate several summaries for each group using aggregate functions.

Example:
```sql
SELECT department_id,
       COUNT(*),
       AVG(salary),
       MAX(salary)
FROM employees
GROUP BY department_id;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display each `department_id` along with the total number of employees.

### Mission 2 (Easy)
Display each product category along with the total number of products and the average product price.

### Mission 3 (Easy+)
Display each customer along with the total number of orders and the total ordered quantity.

### Mission 4 (Medium)
Display each `department_id` with the minimum salary, maximum salary, and average salary.

### Mission 5 (Challenge)
Display each product category with the total stock quantity, average product price, lowest price, and highest price.

---

## 🏆 Bonus Challenge
Display each customer with the minimum and maximum order quantity.

---

## 💡 SQL Tip of the Day
When using `GROUP BY`, every non-aggregated column in the `SELECT` statement must also appear in the `GROUP BY` clause.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll learn how to filter grouped results using the `HAVING` clause.

---

## 📝 Git Commit Message
`Completed Day 42 SQL Mission`

---

## 🎉 Closing Note
You're getting comfortable with one of SQL's most powerful features. Keep practising, stay curious, and enjoy seeing your queries become more insightful every day.
