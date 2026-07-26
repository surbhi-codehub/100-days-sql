
# 🌸 100 Days SQL Journey
## Day 84

## 🌼 Today's Topic
**Multiple Common Table Expressions (CTEs)**

**Goal:** Learn how to use multiple CTEs in a single query to organise complex SQL logic into simple, readable steps.

---

## 💖 A Little Message for Today
Complex SQL doesn't have to be difficult. Breaking a query into smaller building blocks makes it easier to understand, test, and maintain.

---

## 📚 Quick Revision

You can define multiple CTEs by separating them with commas after the `WITH` keyword.

Example:

```sql
WITH HighSalaryEmployees AS (
    SELECT employee_id, first_name, salary
    FROM employees
    WHERE salary > 60000
),
CustomerOrders AS (
    SELECT customer_id, COUNT(*) AS total_orders
    FROM orders
    GROUP BY customer_id
)
SELECT *
FROM CustomerOrders;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Create two CTEs:
- One containing all employees.
- One containing all customers.
Display the results from one CTE.

### Mission 2 (Easy)
Create one CTE for high-paid employees and another for low-stock products. Display both separately.

### Mission 3 (Easy+)
Create one CTE that calculates the total quantity ordered by each customer and another that stores customer details. Join the two CTEs.

### Mission 4 (Medium)
Create one CTE for orders and another for products, then join them to display product names with ordered quantities.

### Mission 5 (Challenge)
Create three CTEs:
- Employee details
- Customer order totals
- Product information

Use them to build a single report combining relevant information where appropriate.

---

## 🏆 Bonus Challenge

Build a query using multiple CTEs where each CTE performs one logical task (filtering, aggregation, and joining). Observe how much easier the query is to read compared to writing everything in a single statement.

---

## 💡 SQL Tip of the Day

Think of each CTE as a small reusable step. Giving meaningful names to CTEs makes complex queries much easier to understand.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to write Recursive CTEs for solving hierarchical and sequence-based problems.

---

## 📝 Git Commit Message

`Completed Day 84 SQL Mission`

---

## 🎉 Closing Note

Excellent work! You're learning how professional SQL developers organise complex queries. Mastering multiple CTEs will help you write cleaner, more maintainable SQL throughout your career.
