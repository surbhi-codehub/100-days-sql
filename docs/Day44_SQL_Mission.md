
# 🌸 100 Days SQL Journey
## Day 44

## 🌼 Today's Topic
**Combining WHERE, GROUP BY, and HAVING**

**Goal:** Learn how to filter rows before grouping and then filter the grouped results.

---

## 💖 A Little Message for Today
SQL becomes more exciting as you combine concepts you've already learned. Keep practising patiently—every challenge you solve is proof that you're improving.

---

## 📚 Quick Revision
- `WHERE` filters rows before grouping.
- `GROUP BY` creates groups.
- `HAVING` filters the grouped results.

Example:
```sql
SELECT department_id, AVG(salary)
FROM employees
WHERE salary > 30000
GROUP BY department_id
HAVING AVG(salary) > 50000;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display each `department_id` and the total number of employees whose salary is greater than 30000. Show only departments with more than 2 employees.

### Mission 2 (Easy)
Display each product category and the average product price for products whose stock quantity is greater than 10. Show only categories where the average price is greater than 1000.

### Mission 3 (Easy+)
Display each customer and the total quantity ordered for orders where the quantity is greater than 1. Show only customers whose total quantity exceeds 5.

### Mission 4 (Medium)
Display each `department_id` with the maximum salary for employees hired after `2022-01-01`. Show only departments where the maximum salary is greater than 70000.

### Mission 5 (Challenge)
Display each product category with the total stock quantity for products priced above 500. Show only categories whose total stock quantity is greater than 100.

---

## 🏆 Bonus Challenge
Display each customer with the total number of orders placed after `2023-01-01`. Show only customers with more than one qualifying order.

---

## 💡 SQL Tip of the Day
A common query order is: `SELECT → FROM → WHERE → GROUP BY → HAVING → ORDER BY`.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll master more practical grouping problems before moving on to SQL joins.

---

## 📝 Git Commit Message
`Completed Day 44 SQL Mission`

---

## 🎉 Closing Note
You're learning to write queries that answer real business questions. Keep building your skills one mission at a time—you're making excellent progress!
