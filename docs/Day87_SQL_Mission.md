
# 🌸 100 Days SQL Journey
## Day 87

## 🌼 Today's Topic
**Managing SQL Views – Updating and Deleting Views**

**Goal:** Learn how to modify existing views and remove views that are no longer needed.

---

## 💖 A Little Message for Today

Creating a view is only the beginning. As business requirements change, you'll often need to update or remove views. Learning to manage them is an important database maintenance skill.

---

## 📚 Quick Revision

Some database systems support updating a view using `CREATE OR REPLACE VIEW`.

Example:

```sql
CREATE OR REPLACE VIEW EmployeeSummary AS
SELECT employee_id, first_name, last_name, salary
FROM employees;
```

To remove a view:

```sql
DROP VIEW EmployeeSummary;
```

> Note: Some databases, such as SQLite, do not support `CREATE OR REPLACE VIEW`. In those systems, you must drop the view and create it again.

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Create a view that displays employee names and salaries.

### Mission 2 (Easy)
Modify the view to include the `department_id` column (or recreate it if your database does not support replacing views).

### Mission 3 (Easy+)
Create a view showing customer names with their cities.

### Mission 4 (Medium)
Drop a view that you created earlier, then recreate it with additional columns.

### Mission 5 (Challenge)
Create a view that joins `customers` and `orders`, test it with a `SELECT` query, then remove the view using `DROP VIEW`.

---

## 🏆 Bonus Challenge

Create two different views:
- One for employee information.
- One for customer order information.

Run queries against both views, then safely remove them using `DROP VIEW`.

---

## 💡 SQL Tip of the Day

Views don't store data—they store SQL queries. Deleting a view removes only the saved query, not the underlying table data.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll begin learning SQL indexes and how they improve query performance.

---

## 📝 Git Commit Message

`Completed Day 87 SQL Mission`

---

## 🎉 Closing Note

Excellent work! You now know how to create, modify, and remove views—an essential skill for maintaining professional SQL databases and reporting solutions.
