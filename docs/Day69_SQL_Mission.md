
# 🌸 100 Days SQL Journey
## Day 69

## 🌼 Today's Topic
**SQL String Functions – Introduction**

**Goal:** Learn how to work with text data using common SQL string functions.

---

## 💖 A Little Message for Today
Text data appears everywhere—customer names, emails, cities, and product categories. Mastering string functions will help you clean and transform this data with ease.

---

## 📚 Quick Revision

String functions allow you to manipulate text values.

Common functions:
- `UPPER()` – Converts text to uppercase.
- `LOWER()` – Converts text to lowercase.
- `LENGTH()` – Returns the length of a string.

Example:

```sql
SELECT
    first_name,
    UPPER(first_name),
    LOWER(first_name),
    LENGTH(first_name)
FROM customers;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display all customer first names in uppercase using `UPPER()`.

### Mission 2 (Easy)
Display all employee last names in lowercase using `LOWER()`.

### Mission 3 (Easy+)
Display each customer's first name along with its character length using `LENGTH()`.

### Mission 4 (Medium)
Display employee first names in both uppercase and lowercase in the same query.

### Mission 5 (Challenge)
Create a report showing customer first names, their uppercase version, lowercase version, and the total number of characters.

---

## 🏆 Bonus Challenge

Find the customer(s) whose first name has the greatest number of characters.

---

## 💡 SQL Tip of the Day

String functions can be combined with other SQL features like `CASE`, `ORDER BY`, and `WHERE` to create cleaner and more meaningful reports.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to join and split text using `CONCAT()` and related string operations.

---

## 📝 Git Commit Message

`Completed Day 69 SQL Mission`

---

## 🎉 Closing Note

Great job! You're beginning a new chapter in SQL by learning how to manipulate text data. These functions are used daily in real-world databases, so keep practising!
