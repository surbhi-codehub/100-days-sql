
# 🌸 100 Days SQL Journey
## Day 55

## 🌼 Today's Topic
**LEFT JOIN – Final Practice**

**Goal:** Master `LEFT JOIN` by solving practical reporting problems that include both matching and non-matching records.

---

## 💖 A Little Message for Today
You've made incredible progress through this module. Every challenge you solve strengthens your SQL skills. Stay consistent, trust the process, and keep enjoying the journey.

---

## 📚 Quick Revision
`LEFT JOIN` returns all rows from the left table and matching rows from the right table.
If there is no matching row, SQL fills the right table's columns with `NULL`.

Example:
```sql
SELECT c.customer_name,
       COUNT(o.order_id) AS total_orders
FROM customers c
LEFT JOIN orders o
ON c.customer_id = o.customer_id
GROUP BY c.customer_name;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display every customer along with the total number of orders. Include customers who have never placed an order.

### Mission 2 (Easy)
Display every department with the total number of employees. Include departments that have no employees.

### Mission 3 (Easy+)
Display every supplier with the average price of the products they supply. Include suppliers without products.

### Mission 4 (Medium)
Display every product together with the total quantity ordered. Include products that have never been ordered.

### Mission 5 (Challenge)
Display every department with the minimum, maximum, and average salary of its employees. Include departments without employees.

---

## 🏆 Bonus Challenge
Display every customer with the total ordered quantity and the maximum order quantity. Customers without orders should still appear.

---

## 💡 SQL Tip of the Day
`LEFT JOIN` is especially useful for finding missing relationships. Look for `NULL` values in the joined table to identify records without matches.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll begin learning **Subqueries**, a powerful way to write queries inside other queries.

---

## 📝 Git Commit Message
`Completed Day 55 SQL Mission`

---

## 🎉 Closing Note
Congratulations on completing the LEFT JOIN module! You're now able to create comprehensive reports that include every important record. Keep practising—your SQL journey is becoming stronger every day.
