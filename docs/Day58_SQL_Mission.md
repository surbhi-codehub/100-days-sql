
# 🌸 100 Days SQL Journey
## Day 58

## 🌼 Today's Topic
**Subqueries with `IN`**

**Goal:** Learn how to use a subquery with the `IN` operator to filter rows based on a list of values returned by another query.

---

## 💖 A Little Message for Today
You're steadily moving into more advanced SQL. Every concept you master gives you another way to solve real business problems. Keep practising with confidence.

---

## 📚 Quick Revision
The `IN` operator checks whether a value exists in a list.
A subquery can generate that list automatically.

Example:
```sql
SELECT employee_name
FROM employees
WHERE department_id IN
(
    SELECT department_id
    FROM departments
    WHERE location = 'Bangalore'
);
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display all employees who belong to departments returned by a subquery.

### Mission 2 (Easy)
Display all products whose supplier is returned by a subquery.

### Mission 3 (Easy+)
Display all orders placed by customers returned by a subquery.

### Mission 4 (Medium)
Display all employees who work in departments having an average salary greater than 60000 using a subquery with `IN`.

### Mission 5 (Challenge)
Display all products belonging to categories whose average product price is greater than the overall average product price.

---

## 🏆 Bonus Challenge
Display all customers who have ordered at least one product whose price is above the average product price by using a subquery.

---

## 💡 SQL Tip of the Day
Use `IN` when your subquery returns multiple values. If it returns only one value, comparison operators such as `=` are usually enough.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll learn how to use `EXISTS` and compare it with `IN`.

---

## 📝 Git Commit Message
`Completed Day 58 SQL Mission`

---

## 🎉 Closing Note
Fantastic work! You're learning to combine SQL concepts into powerful solutions. Stay consistent, keep experimenting, and enjoy the journey.
