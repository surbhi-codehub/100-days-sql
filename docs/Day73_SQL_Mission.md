
# 🌸 100 Days SQL Journey
## Day 73

## 🌼 Today's Topic
**LIKE Operator – Pattern Matching**

**Goal:** Learn how to search for text patterns using the `LIKE` operator with wildcard characters.

---

## 💖 A Little Message for Today
Searching for exact values is useful, but real-world data often requires flexible searches. The `LIKE` operator helps you find records even when you only know part of the text.

---

## 📚 Quick Revision

The `LIKE` operator is used with wildcard characters:

- `%` → Matches zero or more characters.
- `_` → Matches exactly one character.

Examples:

```sql
SELECT *
FROM customers
WHERE first_name LIKE 'A%';
```

```sql
SELECT *
FROM employees
WHERE last_name LIKE '_a%';
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display all customers whose `first_name` starts with the letter **A**.

### Mission 2 (Easy)
Display all employees whose `last_name` ends with the letter **n**.

### Mission 3 (Easy+)
Display all customers whose email contains the word **gmail** using `LIKE`.

### Mission 4 (Medium)
Find all products whose `product_name` contains a specific word or sequence of characters.

### Mission 5 (Challenge)
Create a report showing customers whose `city` starts with a chosen letter and sort the results alphabetically.

---

## 🏆 Bonus Challenge

Write one query using `%` and another using `_`. Compare the results and explain how the two wildcard characters behave differently.

---

## 💡 SQL Tip of the Day

Use `%` when the number of unknown characters can vary, and use `_` when you know exactly one character is missing.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to sort query results using multiple columns with `ORDER BY`.

---

## 📝 Git Commit Message

`Completed Day 73 SQL Mission`

---

## 🎉 Closing Note

Excellent progress! Pattern matching is an essential SQL skill for searching names, emails, cities, and many other types of text. Keep practising, and you'll soon be writing powerful search queries with confidence.
