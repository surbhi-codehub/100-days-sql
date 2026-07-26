
# 🌸 100 Days SQL Journey
## Day 86

## 🌼 Today's Topic
**SQL Views – Creating Virtual Tables**

**Goal:** Learn how to create and use SQL Views to simplify complex queries and reuse them whenever needed.

---

## 💖 A Little Message for Today

You've reached another important milestone. Views allow you to save frequently used queries, making your SQL cleaner, easier to maintain, and more secure.

---

## 📚 Quick Revision

A **View** is a virtual table based on the result of a SQL query. It stores the query, not the data.

Create a view:

```sql
CREATE VIEW EmployeeSummary AS
SELECT employee_id, first_name, last_name, department_id, salary
FROM employees;
```

Use the view:

```sql
SELECT *
FROM EmployeeSummary;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Create a view that displays all columns from the `customers` table.

### Mission 2 (Easy)
Create a view containing employee names and salaries from the `employees` table.

### Mission 3 (Easy+)
Create a view that joins `orders` and `customers` to display customer names with their orders.

### Mission 4 (Medium)
Create a view showing products with `product_name`, `category`, `price`, and `stock_quantity`.

### Mission 5 (Challenge)
Create a view that displays each customer's total ordered quantity using `orders` grouped by `customer_id`.

---

## 🏆 Bonus Challenge

Create a view for a monthly order summary. Then write a separate query that retrieves only the top 5 rows from that view.

---

## 💡 SQL Tip of the Day

Views help reduce duplicate SQL code. If the underlying tables change, updating the view definition can automatically simplify maintenance for many reports.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to modify and remove views using `CREATE OR REPLACE VIEW` (where supported) and `DROP VIEW`.

---

## 📝 Git Commit Message

`Completed Day 86 SQL Mission`

---

## 🎉 Closing Note

Excellent work! Views are widely used in real-world databases to simplify reporting, improve consistency, and make complex SQL easier to manage. Keep practising—you now have another professional SQL tool in your toolkit.
