
# 🌸 100 Days SQL Journey
## Day 70

## 🌼 Today's Topic
**CONCAT() – Combining Text**

**Goal:** Learn how to join multiple text values into a single string using `CONCAT()`.

---

## 💖 A Little Message for Today
Many reports need full names, complete addresses, or formatted messages. Learning to combine text makes your SQL queries much more practical.

---

## 📚 Quick Revision

`CONCAT()` joins two or more strings into one.

Example:

```sql
SELECT CONCAT(first_name, ' ', last_name) AS full_name
FROM employees;
```

Some databases also support the `||` operator for string concatenation.

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display the full name of every employee by combining `first_name` and `last_name`.

### Mission 2 (Easy)
Display the full name of every customer using `CONCAT()`.

### Mission 3 (Easy+)
Create a sentence like **"Customer: John Smith"** for every customer.

### Mission 4 (Medium)
Display employee names along with their city in the format:
**John Smith - Bangalore**

### Mission 5 (Challenge)
Create a formatted order report that combines customer information with order details using `CONCAT()` and appropriate joins.

---

## 🏆 Bonus Challenge

Create a report that displays:
- Employee Full Name
- Job Title
- City

in a single formatted column such as:

`John Smith | Data Analyst | Mumbai`

---

## 💡 SQL Tip of the Day

`CONCAT()` improves readability by creating user-friendly output without changing the stored data.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to extract part of a string using `SUBSTRING()`.

---

## 📝 Git Commit Message

`Completed Day 70 SQL Mission`

---

## 🎉 Closing Note

Congratulations on reaching Day 70! You're steadily building practical SQL skills that are used in real-world reporting and data analysis. Keep going—you've come a long way!
