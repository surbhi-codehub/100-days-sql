
# 🌸 100 Days SQL Journey
## Day 60

## 🌼 Today's Topic
**Subqueries – Final Practice**

**Goal:** Strengthen your understanding of subqueries by solving practical business problems using scalar, `IN`, and `EXISTS` subqueries.

---

## 💖 A Little Message for Today
You've completed another important milestone. The more you practise breaking a problem into smaller queries, the more natural SQL will become. Keep going—your consistency is paying off.

---

## 📚 Quick Revision
A subquery is a query inside another query.
It can return a single value, multiple values, or simply check whether matching rows exist.

Example:
```sql
SELECT employee_name
FROM employees
WHERE department_id IN (
    SELECT department_id
    FROM departments
    WHERE location = 'Bangalore'
);
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display all employees whose salary is greater than the average salary of all employees.

### Mission 2 (Easy)
Display all products whose price is greater than the average price of products in their category.

### Mission 3 (Easy+)
Display all customers who have placed at least one order using a subquery.

### Mission 4 (Medium)
Display all departments that have more employees than the average number of employees per department using a subquery.

### Mission 5 (Challenge)
Display all products that have never been ordered using a suitable subquery.

---

## 🏆 Bonus Challenge
Display the customer(s) who placed the order with the highest quantity using a subquery.

---

## 💡 SQL Tip of the Day
When a query feels complicated, solve the inner query first. Once it returns the correct result, plug it into the outer query.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll begin learning the `CASE` expression to add conditional logic to your SQL queries.

---

## 📝 Git Commit Message
`Completed Day 60 SQL Mission`

---

## 🎉 Closing Note
Congratulations on completing the Subqueries module! You've learned one of SQL's most powerful techniques. Keep practising, and you're ready for the next chapter of your SQL journey.
