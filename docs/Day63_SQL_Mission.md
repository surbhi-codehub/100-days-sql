
# 🌸 100 Days SQL Journey
## Day 63

## 🌼 Today's Topic
**NULL – Introduction**

**Goal:** Learn what `NULL` means in SQL and how to identify missing values using `IS NULL` and `IS NOT NULL`.

---

## 💖 A Little Message for Today
Not every database is perfect, and that's completely normal. Learning how to work with missing values is an important skill that will help you build reliable SQL queries.

---

## 📚 Quick Revision
`NULL` represents a missing or unknown value.
You cannot compare it using `=` or `!=`.
Use `IS NULL` or `IS NOT NULL` instead.

Example:
```sql
SELECT employee_name
FROM employees
WHERE manager_id IS NULL;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display all records where a nullable column contains `NULL`.

### Mission 2 (Easy)
Display all records where a nullable column is **not** `NULL`.

### Mission 3 (Easy+)
Count how many rows contain `NULL` in a chosen nullable column.

### Mission 4 (Medium)
Display products (or other entities) that do not have related optional information by checking for `NULL` after a `LEFT JOIN`.

### Mission 5 (Challenge)
Create a report that classifies rows as **Available** or **Missing** based on whether a nullable column contains a value.

---

## 🏆 Bonus Challenge
Display the total number of rows with missing values and non-missing values in the same report.

---

## 💡 SQL Tip of the Day
Never use `= NULL` or `<> NULL`. Always use `IS NULL` or `IS NOT NULL` when checking for missing values.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll learn how to replace missing values using the `COALESCE()` function.

---

## 📝 Git Commit Message
`Completed Day 63 SQL Mission`

---

## 🎉 Closing Note
Great job! Understanding `NULL` is essential for writing accurate SQL queries. Keep practising, and handling missing data will soon become second nature.
