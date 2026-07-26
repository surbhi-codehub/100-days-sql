
# 🌸 100 Days SQL Journey
## Day 57

## 🌼 Today's Topic
**Subqueries in the WHERE Clause**

**Goal:** Learn how to use subqueries inside the `WHERE` clause to filter data dynamically.

---

## 💖 A Little Message for Today
You're learning techniques that professional SQL developers use every day. Focus on understanding the logic step by step, and every query will become easier to solve.

---

## 📚 Quick Revision
A subquery inside the `WHERE` clause provides a value or a list of values that the outer query uses for filtering.

Example:
```sql
SELECT product_name
FROM products
WHERE price >
(
    SELECT AVG(price)
    FROM products
);
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display all employees whose salary is greater than the average salary.

### Mission 2 (Easy)
Display all products whose price is less than the average product price.

### Mission 3 (Easy+)
Display all orders whose quantity is greater than the average order quantity.

### Mission 4 (Medium)
Display the employees who belong to the department with the highest average salary.

### Mission 5 (Challenge)
Display the customers who have placed more orders than the average number of orders per customer using a subquery.

---

## 🏆 Bonus Challenge
Display the products whose stock quantity is greater than the maximum stock quantity of products in a different category (use a suitable subquery based on the database).

---

## 💡 SQL Tip of the Day
Write and test the inner query first. Once it returns the expected result, place it inside the outer query.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll learn how to use subqueries with the `IN` operator.

---

## 📝 Git Commit Message
`Completed Day 57 SQL Mission`

---

## 🎉 Closing Note
You're building the ability to solve more advanced SQL problems with confidence. Keep practising consistently, and complex queries will soon feel natural.
