
# 🌸 100 Days SQL Journey
## Day 75

## 🌼 Today's Topic
**LIMIT – Returning a Fixed Number of Rows**

**Goal:** Learn how to return only a specific number of rows using the `LIMIT` clause.

---

## 💖 A Little Message for Today
Databases can contain thousands or even millions of records. Instead of viewing everything, SQL lets you quickly retrieve just the rows you need.

---

## 📚 Quick Revision

The `LIMIT` clause restricts the number of rows returned by a query.

Example:

```sql
SELECT *
FROM employees
LIMIT 5;
```

You can combine `LIMIT` with `ORDER BY` to retrieve the top or bottom records.

Example:

```sql
SELECT first_name, salary
FROM employees
ORDER BY salary DESC
LIMIT 3;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display the first **5** records from the `customers` table.

### Mission 2 (Easy)
Display the first **10** products from the `products` table.

### Mission 3 (Easy+)
Display the **5 highest-paid employees** using `ORDER BY` and `LIMIT`.

### Mission 4 (Medium)
Display the **3 most recent orders** using `order_date` and `LIMIT`.

### Mission 5 (Challenge)
Create a report showing the **top 5 most expensive products**, displaying `product_name`, `category`, and `price`.

---

## 🏆 Bonus Challenge

Create two queries:
1. Display the **5 lowest-paid employees**.
2. Display the **5 highest-paid employees**.

Compare the two result sets and explain how `ORDER BY` affects `LIMIT`.

---

## 💡 SQL Tip of the Day

`LIMIT` becomes much more powerful when combined with `ORDER BY`, allowing you to retrieve top-performing, newest, oldest, cheapest, or most expensive records.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to skip rows using `OFFSET` and combine it with `LIMIT` for pagination.

---

## 📝 Git Commit Message

`Completed Day 75 SQL Mission`

---

## 🎉 Closing Note

Congratulations on reaching Day 75! You're now learning techniques used in dashboards, reports, and applications every day. Keep building your SQL skills—you're making excellent progress!
