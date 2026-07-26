
# 🌸 100 Days SQL Journey
## Day 83

## 🌼 Today's Topic
**Common Table Expressions (CTEs) – Introduction**

**Goal:** Learn how to use Common Table Expressions (CTEs) to write cleaner, more readable, and reusable SQL queries.

---

## 💖 A Little Message for Today
As SQL queries become more complex, readability becomes just as important as correctness. CTEs help you break a large query into smaller, logical steps that are easier to understand and maintain.

---

## 📚 Quick Revision

A Common Table Expression (CTE) is a temporary named result set created using the `WITH` keyword. It exists only for the duration of the query.

Example:

```sql
WITH HighSalaryEmployees AS (
    SELECT employee_id, first_name, last_name, salary
    FROM employees
    WHERE salary > 60000
)
SELECT *
FROM HighSalaryEmployees;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Create a CTE that displays all employees from the `employees` table.

### Mission 2 (Easy)
Create a CTE containing employees with a salary above a chosen amount, then display all rows from the CTE.

### Mission 3 (Easy+)
Create a CTE that stores products with `stock_quantity` below a chosen value and display the results.

### Mission 4 (Medium)
Create a CTE that joins `orders` and `customers`, then display customer names along with their order details.

### Mission 5 (Challenge)
Create a CTE that calculates the total quantity ordered by each customer, then display only customers whose total quantity exceeds a chosen threshold.

---

## 🏆 Bonus Challenge

Create two CTEs in the same query:
- One for high-paid employees.
- One for low-stock products.

Display the results from each CTE separately and observe how CTEs improve query organisation.

---

## 💡 SQL Tip of the Day

CTEs don't permanently store data. They simply make complex queries easier to read, debug, and maintain.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to use multiple CTEs together to solve more advanced SQL problems.

---

## 📝 Git Commit Message

`Completed Day 83 SQL Mission`

---

## 🎉 Closing Note

Fantastic work! You've started using one of the most valuable SQL features for writing professional-quality queries. Keep practising with CTEs, and complex SQL will soon feel much easier to manage.
