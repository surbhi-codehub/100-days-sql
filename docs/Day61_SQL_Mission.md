
# 🌸 100 Days SQL Journey
## Day 61

## 🌼 Today's Topic
**CASE Expression – Introduction**

**Goal:** Learn how to use the `CASE` expression to return different values based on conditions.

---

## 💖 A Little Message for Today
You're entering a stage where SQL becomes even more expressive. Small conditional statements can make your reports much more meaningful. Keep exploring and enjoy the process.

---

## 📚 Quick Revision
The `CASE` expression works like an IF–ELSE statement in SQL.

Example:
```sql
SELECT employee_name,
       salary,
       CASE
           WHEN salary >= 70000 THEN 'High'
           WHEN salary >= 50000 THEN 'Medium'
           ELSE 'Low'
       END AS salary_level
FROM employees;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display each employee's name and classify their salary as **High** or **Low** using `CASE`.

### Mission 2 (Easy)
Display each product with a label **Expensive** or **Affordable** based on its price.

### Mission 3 (Easy+)
Display each order and label it as **Bulk Order** or **Regular Order** based on the order quantity.

### Mission 4 (Medium)
Display each employee with a salary band such as **Low**, **Medium**, or **High** using multiple `WHEN` conditions.

### Mission 5 (Challenge)
Display each product with a stock status such as **Out of Stock**, **Low Stock**, or **In Stock** using `CASE`.

---

## 🏆 Bonus Challenge
Create a report that shows each customer together with an **Active** or **Inactive** label depending on whether they have placed at least one order.

---

## 💡 SQL Tip of the Day
`CASE` can be used in both the `SELECT` and `ORDER BY` clauses to create more meaningful reports.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll practise using `CASE` together with aggregate functions and grouping.

---

## 📝 Git Commit Message
`Completed Day 61 SQL Mission`

---

## 🎉 Closing Note
Excellent work! You've started learning conditional logic in SQL. Keep practising, and you'll soon be able to create reports that are both powerful and easy to understand.
