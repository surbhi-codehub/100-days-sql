
# 🌸 100 Days SQL Journey
## Day 51

## 🌼 Today's Topic
**LEFT JOIN – Introduction**

**Goal:** Learn how to return all rows from the left table, even when there is no matching row in the related table.

---

## 💖 A Little Message for Today
You're entering another important chapter of SQL. Don't worry if `LEFT JOIN` feels a little different at first—practice will make it clear. Keep enjoying the journey.

---

## 📚 Quick Revision
`LEFT JOIN` returns every row from the left table and only the matching rows from the right table. If there is no match, the columns from the right table contain `NULL`.

Example:
```sql
SELECT c.customer_name,
       o.order_id
FROM customers c
LEFT JOIN orders o
ON c.customer_id = o.customer_id;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display all customers along with their orders. Include customers who have not placed any orders.

### Mission 2 (Easy)
Display all departments along with their employees. Include departments that currently have no employees.

### Mission 3 (Easy+)
Display all suppliers along with their products. Include suppliers that do not supply any products.

### Mission 4 (Medium)
Display all products together with their order details. Include products that have never been ordered.

### Mission 5 (Challenge)
Display every customer with the total number of orders placed. Customers with no orders should also appear in the result.

---

## 🏆 Bonus Challenge
Display all departments with the average salary of their employees. Departments without employees should still be included.

---

## 💡 SQL Tip of the Day
Choose `LEFT JOIN` when you want to keep every record from the left table, even if related data doesn't exist in the right table.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll practise `LEFT JOIN` with aggregate functions and real-world reporting queries.

---

## 📝 Git Commit Message
`Completed Day 51 SQL Mission`

---

## 🎉 Closing Note
Great work reaching Day 51! You're learning how to find not only matching data but also missing information—a valuable skill in real-world SQL.
