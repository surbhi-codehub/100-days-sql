
# 🌸 100 Days SQL Journey
## Day 45

## 🌼 Today's Topic
**GROUP BY & HAVING – Practice Day**

**Goal:** Strengthen your understanding of `WHERE`, `GROUP BY`, and `HAVING` by solving practical business scenarios.

---

## 💖 A Little Message for Today
The best way to master SQL is through practice. Every query you write sharpens your thinking and helps you recognise patterns more quickly. Keep going—you are making steady progress.

---

## 📚 Quick Revision
- `WHERE` filters rows before grouping.
- `GROUP BY` creates groups of similar values.
- `HAVING` filters the grouped results.

Example:
```sql
SELECT category,
       COUNT(*)
FROM products
WHERE price > 500
GROUP BY category
HAVING COUNT(*) >= 3;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display each `department_id` with the total number of employees. Show only departments having at least 2 employees.

### Mission 2 (Easy)
Display each product category with the total number of products priced above 500. Show only categories having more than 2 products.

### Mission 3 (Easy+)
Display each customer with the total quantity ordered where the order quantity is at least 2. Show only customers whose total quantity is greater than 8.

### Mission 4 (Medium)
Display each `department_id` with the average salary of employees earning more than 40000. Show only departments whose average salary exceeds 60000.

### Mission 5 (Challenge)
Display each product category with the total stock quantity for products whose price is greater than 1000. Show only categories whose total stock quantity exceeds 150.

---

## 🏆 Bonus Challenge
Display each customer with the total number of orders and the maximum order quantity. Show only customers who have placed more than one order.

---

## 💡 SQL Tip of the Day
Remember the execution flow: `FROM → WHERE → GROUP BY → HAVING → SELECT → ORDER BY`. Understanding this makes debugging much easier.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll complete the final advanced practice on grouping before moving to SQL joins.

---

## 📝 Git Commit Message
`Completed Day 45 SQL Mission`

---

## 🎉 Closing Note
You've completed another milestone. Keep practising with confidence, and you'll soon be writing SQL queries that solve real-world business problems with ease.
