
# 🌸 100 Days SQL Journey
## Day 52

## 🌼 Today's Topic
**LEFT JOIN with Aggregate Functions**

**Goal:** Learn how to combine `LEFT JOIN` with aggregate functions to create reports that include records with no matching data.

---

## 💖 A Little Message for Today
Real-world databases often contain incomplete relationships. Learning how to report both existing and missing data makes you a stronger SQL developer. Keep practising—you’re doing great!

---

## 📚 Quick Revision
`LEFT JOIN` keeps all rows from the left table.
Aggregate functions can summarize the matching rows while still showing records without matches.

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
Display every customer with the total number of orders placed. Include customers who have never placed an order.

### Mission 2 (Easy)
Display every department with the total number of employees. Include departments without employees.

### Mission 3 (Easy+)
Display every supplier with the total number of products they supply. Include suppliers with no products.

### Mission 4 (Medium)
Display every product with the total quantity ordered. Include products that have never been ordered.

### Mission 5 (Challenge)
Display every department with the average salary of its employees. Include departments that currently have no employees.

---

## 🏆 Bonus Challenge
Display every customer with the maximum order quantity they have placed. Customers with no orders should still appear.

---

## 💡 SQL Tip of the Day
When using `COUNT()` with a `LEFT JOIN`, count a column from the right table (such as `order_id`) instead of `COUNT(*)` to avoid counting unmatched rows.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll solve more practical reporting problems using `LEFT JOIN`.

---

## 📝 Git Commit Message
`Completed Day 52 SQL Mission`

---

## 🎉 Closing Note
Excellent progress! You're learning how to build reports that don't miss important information. Keep practising, and these queries will soon become second nature.
