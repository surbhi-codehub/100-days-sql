
# 🌸 100 Days SQL Journey
## Day 66

## 🌼 Today's Topic
**UNION – Introduction**

**Goal:** Learn how to combine the results of two or more `SELECT` queries using the `UNION` operator.

---

## 💖 A Little Message for Today
You're stepping into another powerful SQL feature. Learning how to combine results from different queries will help you create flexible and insightful reports. Stay curious and keep practising.

---

## 📚 Quick Revision
`UNION` combines the results of two or more `SELECT` statements into a single result set.
Each query must return the same number of columns with compatible data types.
`UNION` automatically removes duplicate rows.

Example:
```sql
SELECT customer_name
FROM customers

UNION

SELECT supplier_name
FROM suppliers;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Combine the names from two different tables into a single result using `UNION`.

### Mission 2 (Easy)
Display IDs from two related tables in one result using `UNION`.

### Mission 3 (Easy+)
Combine employee names and customer names into a single list with one column.

### Mission 4 (Medium)
Display product categories from different product groups using `UNION`, ensuring duplicates are removed.

### Mission 5 (Challenge)
Create a single report that combines records from two tables with matching column structures using `UNION`.

---

## 🏆 Bonus Challenge
Combine customer names and supplier names into one list, sorted alphabetically.

---

## 💡 SQL Tip of the Day
Use `UNION` when you want unique results. If you need to keep duplicate rows, you'll learn `UNION ALL` later.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll explore `UNION ALL` and discover how it differs from `UNION`.

---

## 📝 Git Commit Message
`Completed Day 66 SQL Mission`

---

## 🎉 Closing Note
Well done! You've started learning how to merge results from multiple queries. Keep experimenting with different combinations, and your SQL skills will continue to grow.
