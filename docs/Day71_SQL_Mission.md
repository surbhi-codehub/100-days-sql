
# 🌸 100 Days SQL Journey
## Day 71

## 🌼 Today's Topic
**SUBSTRING() – Extracting Part of a String**

**Goal:** Learn how to extract a portion of text from a string using the `SUBSTRING()` function.

---

## 💖 A Little Message for Today
Not every report needs the complete text. Sometimes you only need the first few letters, a domain name, or a specific section of a value. `SUBSTRING()` helps you do exactly that.

---

## 📚 Quick Revision

`SUBSTRING()` extracts a specified part of a string.

Example:

```sql
SELECT
    first_name,
    SUBSTRING(first_name, 1, 3) AS short_name
FROM customers;
```

> The exact syntax may vary slightly depending on the database system, but the idea remains the same.

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display the first three characters of every customer's `first_name`.

### Mission 2 (Easy)
Display the first two characters of every employee's `last_name`.

### Mission 3 (Easy+)
Display each customer's email along with the first five characters of the email.

### Mission 4 (Medium)
Create a report showing employee `first_name` and an abbreviated version containing only the first four characters.

### Mission 5 (Challenge)
Display customer names along with a shortened version of their names and sort the result alphabetically by the shortened value.

---

## 🏆 Bonus Challenge

Create a report that displays:
- Customer Full Name
- First 3 characters of the first name
- First 3 characters of the last name

using `SUBSTRING()`.

---

## 💡 SQL Tip of the Day

`SUBSTRING()` is commonly used for formatting reports, masking sensitive data, and extracting meaningful parts of text values.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to remove unwanted spaces from text using `TRIM()`, `LTRIM()`, and `RTRIM()`.

---

## 📝 Git Commit Message

`Completed Day 71 SQL Mission`

---

## 🎉 Closing Note

Fantastic work! You're becoming more comfortable manipulating text in SQL. Small string functions like `SUBSTRING()` are widely used in reporting, ETL processes, and data cleaning.
