
# 🌸 100 Days SQL Journey
## Day 43

## 🌼 Today's Topic
**HAVING Clause – Introduction**

**Goal:** Learn how to filter grouped results after using `GROUP BY`.

---

## 💖 A Little Message for Today
You've already learned how to group data. Today you'll learn how to keep only the groups that matter. Every new concept adds another powerful tool to your SQL toolkit.

---

## 📚 Quick Revision
`WHERE` filters rows **before** grouping.
`HAVING` filters groups **after** `GROUP BY`.

Example:
```sql
SELECT department_id, COUNT(*)
FROM employees
GROUP BY department_id
HAVING COUNT(*) > 2;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display each `department_id` and the number of employees. Show only departments that have more than 2 employees.

### Mission 2 (Easy)
Display each product category and the total number of products. Show only categories with more than 5 products.

### Mission 3 (Easy+)
Display each customer and the total number of orders. Show only customers who placed more than 1 order.

### Mission 4 (Medium)
Display each `department_id` and the average salary. Show only departments where the average salary is greater than 50000.

### Mission 5 (Challenge)
Display each product category with the total stock quantity. Show only categories where the total stock quantity is greater than 100.

---

## 🏆 Bonus Challenge
Display each customer with the total ordered quantity. Show only customers whose total ordered quantity is greater than 10.

---

## 💡 SQL Tip of the Day
Use `WHERE` to filter individual rows and `HAVING` to filter grouped results. They often work together in the same query.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll combine `WHERE`, `GROUP BY`, and `HAVING` to solve more realistic business problems.

---

## 📝 Git Commit Message
`Completed Day 43 SQL Mission`

---

## 🎉 Closing Note
Great job! You're learning how to turn raw data into meaningful insights. Keep practising, and each day's mission will make SQL feel more natural.
