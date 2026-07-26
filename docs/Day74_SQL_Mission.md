
# 🌸 100 Days SQL Journey
## Day 74

## 🌼 Today's Topic
**ORDER BY – Sorting Data Using Multiple Columns**

**Goal:** Learn how to sort query results using more than one column with the `ORDER BY` clause.

---

## 💖 A Little Message for Today
Good reports aren't just accurate—they're easy to read. Sorting data in a meaningful way helps users quickly find the information they need.

---

## 📚 Quick Revision

The `ORDER BY` clause sorts query results.

- `ASC` → Ascending order (default)
- `DESC` → Descending order
- You can sort by multiple columns by separating them with commas.

Example:

```sql
SELECT first_name, last_name, city
FROM customers
ORDER BY city ASC, first_name ASC;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display all customers sorted by `first_name` in ascending order.

### Mission 2 (Easy)
Display all employees sorted by `salary` in descending order.

### Mission 3 (Easy+)
Display all products sorted first by `category` and then by `price` in ascending order.

### Mission 4 (Medium)
Display all employees sorted by `department_id` and then by `hire_date`.

### Mission 5 (Challenge)
Create a report showing customer orders sorted by `customer_id` and `order_date`, with the most recent orders appearing first within each customer.

---

## 🏆 Bonus Challenge

Create two reports:
1. Sort employees by `city` and then `last_name`.
2. Sort products by `stock_quantity` (highest first) and then `product_name` alphabetically.

Compare how changing the order of columns in `ORDER BY` changes the result.

---

## 💡 SQL Tip of the Day

SQL sorts by the first column listed in `ORDER BY`. If multiple rows have the same value, it uses the next column to determine their order.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to limit the number of rows returned using `LIMIT`.

---

## 📝 Git Commit Message

`Completed Day 74 SQL Mission`

---

## 🎉 Closing Note

Great work! Sorting data is one of the most frequently used SQL skills. Mastering multi-column sorting will help you create professional, easy-to-read reports.
