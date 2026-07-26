
# 🌸 100 Days SQL Journey
## Day 72

## 🌼 Today's Topic
**TRIM(), LTRIM(), and RTRIM() – Removing Unwanted Spaces**

**Goal:** Learn how to remove leading, trailing, and extra surrounding spaces from text values.

---

## 💖 A Little Message for Today
Real-world data is often messy. Extra spaces can cause incorrect comparisons and untidy reports. Today's functions will help you clean text before using it.

---

## 📚 Quick Revision

- `TRIM()` removes spaces from both the beginning and end of a string.
- `LTRIM()` removes spaces from the left (beginning).
- `RTRIM()` removes spaces from the right (end).

Example:

```sql
SELECT
    first_name,
    TRIM(first_name) AS cleaned_name
FROM customers;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display customer `first_name` values after applying `TRIM()`.

### Mission 2 (Easy)
Display employee `last_name` values using `LTRIM()`.

### Mission 3 (Easy+)
Display customer email addresses after applying `RTRIM()`.

### Mission 4 (Medium)
Create a report showing the original `first_name` and the trimmed version side by side.

### Mission 5 (Challenge)
Use `TRIM()` together with `CONCAT()` to display neatly formatted full names for employees.

---

## 🏆 Bonus Challenge

Create a report displaying:
- Original first name
- Trimmed first name
- Character length before trimming
- Character length after trimming

using `LENGTH()` and `TRIM()`.

---

## 💡 SQL Tip of the Day

Cleaning text before filtering, joining, or comparing values helps prevent unexpected results caused by unwanted spaces.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to search for patterns in text using the `LIKE` operator and wildcard characters.

---

## 📝 Git Commit Message

`Completed Day 72 SQL Mission`

---

## 🎉 Closing Note

Excellent work! Data cleaning is a fundamental SQL skill. Mastering these simple functions will make your queries more reliable and your reports more professional.
