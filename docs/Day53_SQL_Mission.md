
# 🌸 100 Days SQL Journey
## Day 53

## 🌼 Today's Topic
**LEFT JOIN – Practical Business Reports**

**Goal:** Strengthen your understanding of `LEFT JOIN` by solving reporting queries that include matching and non-matching records.

---

## 💖 A Little Message for Today
You're learning one of the most practical SQL techniques used in reporting. Keep exploring, make mistakes, and learn from them. Every query makes you a stronger problem solver.

---

## 📚 Quick Revision
`LEFT JOIN` returns all rows from the left table and matching rows from the right table. If no match exists, the right table columns contain `NULL`.

Example:
```sql
SELECT d.department_name,
       COUNT(e.employee_id) AS total_employees
FROM departments d
LEFT JOIN employees e
ON d.department_id = e.department_id
GROUP BY d.department_name;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display every customer along with the number of orders they have placed. Include customers with no orders.

### Mission 2 (Easy)
Display every department along with the average salary of its employees. Include departments without employees.

### Mission 3 (Easy+)
Display every supplier together with the number of products they supply. Include suppliers that currently supply no products.

### Mission 4 (Medium)
Display every product with the total quantity ordered. Include products that have never been ordered.

### Mission 5 (Challenge)
Display every customer with the total number of orders and the total quantity ordered. Customers with no orders should still appear.

---

## 🏆 Bonus Challenge
Display every department with the highest salary of its employees. Departments without employees should also appear.

---

## 💡 SQL Tip of the Day
When using `LEFT JOIN`, remember that aggregate functions like `COUNT(column)` ignore `NULL` values, making them useful for finding missing relationships.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll continue practising `LEFT JOIN` with more advanced reporting scenarios.

---

## 📝 Git Commit Message
`Completed Day 53 SQL Mission`

---

## 🎉 Closing Note
You're becoming more confident with SQL reporting. Keep practising these real-world scenarios, and you'll be ready to analyse data from complex databases with ease.
