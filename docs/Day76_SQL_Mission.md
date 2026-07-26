
# 🌸 100 Days SQL Journey
## Day 76

## 🌼 Today's Topic
**OFFSET – Skipping Rows for Pagination**

**Goal:** Learn how to use the `OFFSET` clause with `LIMIT` to skip rows and retrieve data in pages.

---

## 💖 A Little Message for Today
Large datasets are easier to explore when you can view them one page at a time. `OFFSET` helps you navigate through records without loading everything at once.

---

## 📚 Quick Revision

- `LIMIT` controls how many rows are returned.
- `OFFSET` skips a specified number of rows before returning results.
- `ORDER BY` should usually be used with `LIMIT` and `OFFSET` to ensure consistent results.

Example:

```sql
SELECT *
FROM customers
ORDER BY customer_id
LIMIT 5 OFFSET 5;
```

The query skips the first 5 rows and returns the next 5.

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display the first 5 customers using `LIMIT`.

### Mission 2 (Easy)
Skip the first 5 customers and display the next 5 using `LIMIT` and `OFFSET`.

### Mission 3 (Easy+)
Display products 11–20 by combining `ORDER BY`, `LIMIT`, and `OFFSET`.

### Mission 4 (Medium)
Display employees in batches of 10 records, starting from the 21st record.

### Mission 5 (Challenge)
Create a report showing the 5 most recent orders after skipping the first 10 most recent orders.

---

## 🏆 Bonus Challenge

Write three queries to display:
1. Rows 1–5
2. Rows 6–10
3. Rows 11–15

using `LIMIT` and `OFFSET`, and compare the outputs.

---

## 💡 SQL Tip of the Day

`OFFSET` is commonly used for pagination in web applications, allowing users to browse data page by page.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to retrieve unique values using the `DISTINCT` keyword.

---

## 📝 Git Commit Message

`Completed Day 76 SQL Mission`

---

## 🎉 Closing Note

Excellent work! You've learned another practical SQL feature used in dashboards, reports, and applications. Keep practising with different `LIMIT` and `OFFSET` values to become comfortable with pagination.
