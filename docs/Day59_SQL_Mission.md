
# 🌸 100 Days SQL Journey
## Day 59

## 🌼 Today's Topic
**Subqueries with `EXISTS`**

**Goal:** Learn how to use the `EXISTS` operator with subqueries to check whether matching rows exist.

---

## 💖 A Little Message for Today
Every new SQL concept expands the kinds of problems you can solve. Don't rush—understanding the logic is far more valuable than memorising syntax.

---

## 📚 Quick Revision
`EXISTS` returns **TRUE** if the subquery finds at least one matching row.
It is commonly used with **correlated subqueries**.

Example:
```sql
SELECT customer_name
FROM customers c
WHERE EXISTS (
    SELECT 1
    FROM orders o
    WHERE o.customer_id = c.customer_id
);
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display all customers who have placed at least one order using `EXISTS`.

### Mission 2 (Easy)
Display all suppliers who supply at least one product using `EXISTS`.

### Mission 3 (Easy+)
Display all departments that have at least one employee using `EXISTS`.

### Mission 4 (Medium)
Display all products that have appeared in at least one order using `EXISTS`.

### Mission 5 (Challenge)
Display all customers who have placed an order with a quantity greater than 5 using `EXISTS`.

---

## 🏆 Bonus Challenge
Display all departments where at least one employee earns more than 70000 using `EXISTS`.

---

## 💡 SQL Tip of the Day
Use `EXISTS` when you only need to know whether matching rows exist. It can be more efficient than other approaches because SQL can stop searching after finding the first match.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll wrap up subqueries with practical business scenarios before moving on to conditional expressions.

---

## 📝 Git Commit Message
`Completed Day 59 SQL Mission`

---

## 🎉 Closing Note
You're steadily building advanced SQL skills. Keep practising, keep experimenting, and enjoy watching your confidence grow with every challenge.
