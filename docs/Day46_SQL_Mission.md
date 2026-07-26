
# 🌸 100 Days SQL Journey
## Day 46

## 🌼 Today's Topic
**Advanced GROUP BY & HAVING Practice**

**Goal:** Improve your ability to analyse grouped data by combining filtering, aggregation, and grouping in practical business scenarios.

---

## 💖 A Little Message for Today
You're getting closer to thinking like a data analyst. Every practice session improves both your SQL skills and your problem-solving ability. Stay consistent—the results will follow.

---

## 📚 Quick Revision
`GROUP BY` creates one summary row for each group.
`HAVING` filters those groups after the aggregate values have been calculated.

Example:
```sql
SELECT department_id,
       COUNT(*) AS total_employees,
       AVG(salary) AS average_salary
FROM employees
GROUP BY department_id
HAVING AVG(salary) > 50000;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display each `department_id` with the total number of employees. Show only departments with at least 3 employees.

### Mission 2 (Easy)
Display each product category with the average product price. Show only categories where the average price is greater than 750.

### Mission 3 (Easy+)
Display each customer with the total quantity ordered. Include only orders where the quantity is greater than 1, and show customers whose total quantity is greater than 10.

### Mission 4 (Medium)
Display each `department_id` with the minimum salary, maximum salary, and average salary for employees earning more than 30000. Show only departments where the maximum salary exceeds 80000.

### Mission 5 (Challenge)
Display each product category with the total stock quantity, minimum price, maximum price, and average price for products priced above 500. Show only categories where the total stock quantity is greater than 100.

---

## 🏆 Bonus Challenge
Display each customer with the total number of orders and the average order quantity. Show only customers who have placed more than two orders.

---

## 💡 SQL Tip of the Day
Give meaningful aliases to aggregate columns using `AS` to make your query results easier to understand.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll complete the final `GROUP BY` and `HAVING` practice before starting SQL joins.

---

## 📝 Git Commit Message
`Completed Day 46 SQL Mission`

---

## 🎉 Closing Note
Excellent work! You're becoming more comfortable with data summarisation and analysis. Keep practising regularly, and you'll be well prepared for SQL joins.
