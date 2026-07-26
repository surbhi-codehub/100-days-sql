
# 🌸 100 Days SQL Journey
## Day 47

## 🌼 Today's Topic
**GROUP BY & HAVING – Final Practice**

**Goal:** Build confidence by solving realistic reporting questions using `WHERE`, `GROUP BY`, and `HAVING` together.

---

## 💖 A Little Message for Today
You've reached the final stage of this module. Every query you complete is proof that your SQL skills are growing. Stay consistent, and the complex queries ahead will feel much easier.

---

## 📚 Quick Revision
`GROUP BY` creates groups of similar records.
Aggregate functions calculate summaries for each group.
`HAVING` filters those groups after the calculations.

Example:
```sql
SELECT department_id,
       COUNT(*) AS total_employees,
       AVG(salary) AS average_salary
FROM employees
WHERE salary > 30000
GROUP BY department_id
HAVING COUNT(*) >= 2;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display each `department_id` with the total number of employees. Show only departments having at least 2 employees.

### Mission 2 (Easy)
Display each product category with the average product price for products whose stock quantity is greater than 20. Show only categories where the average price is greater than 1000.

### Mission 3 (Easy+)
Display each customer with the total number of orders and total ordered quantity. Show only customers whose total ordered quantity is greater than 15.

### Mission 4 (Medium)
Display each `department_id` with the minimum, maximum, and average salary for employees hired after `2022-01-01`. Show only departments where the average salary is greater than 60000.

### Mission 5 (Challenge)
Display each product category with the total stock quantity, average price, minimum price, and maximum price for products priced above 500. Show only categories whose total stock quantity exceeds 200.

---

## 🏆 Bonus Challenge
Display each customer with the maximum order quantity. Show only customers who have placed more than two orders.

---

## 💡 SQL Tip of the Day
Use clear column aliases such as `total_orders` or `average_salary` to make your query output easier to read.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll begin learning **INNER JOIN** and discover how to combine data from multiple tables.

---

## 📝 Git Commit Message
`Completed Day 47 SQL Mission`

---

## 🎉 Closing Note
Fantastic work completing the grouping module! You now have a solid foundation for analysing data. Get ready to unlock even more powerful SQL techniques with joins.
