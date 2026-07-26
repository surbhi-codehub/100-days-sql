
# 🌸 100 Days SQL Journey
## Day 56

## 🌼 Today's Topic
**Subqueries – Introduction**

**Goal:** Learn how to write a query inside another query to solve more advanced SQL problems.

---

## 💖 A Little Message for Today
You've reached another exciting milestone. Subqueries may seem challenging at first, but once you understand the pattern, they'll become one of your favourite SQL tools. Stay patient and keep practising.

---

## 📚 Quick Revision
A **subquery** is a query written inside another SQL query.
The inner query runs first, and its result is used by the outer query.

Example:
```sql
SELECT employee_name
FROM employees
WHERE salary >
(
    SELECT AVG(salary)
    FROM employees
);
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display the names of employees whose salary is greater than the average salary of all employees.

### Mission 2 (Easy)
Display the products whose price is greater than the average product price.

### Mission 3 (Easy+)
Display the customers who have placed more orders than the average number of orders per customer.

### Mission 4 (Medium)
Display the employees who work in the department that has the highest average salary.

### Mission 5 (Challenge)
Display the products whose stock quantity is less than the average stock quantity of all products.

---

## 🏆 Bonus Challenge
Display the customers who placed an order with the maximum order quantity.

---

## 💡 SQL Tip of the Day
Start by writing and testing the inner query first. Once it returns the correct result, use it inside the outer query.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll practise subqueries in the `WHERE` clause using real-world business questions.

---

## 📝 Git Commit Message
`Completed Day 56 SQL Mission`

---

## 🎉 Closing Note
Great job starting the Subqueries module! Keep breaking big problems into smaller queries, and you'll discover just how powerful SQL can be.
