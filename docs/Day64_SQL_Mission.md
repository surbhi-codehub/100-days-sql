
# 🌸 100 Days SQL Journey
## Day 64

## 🌼 Today's Topic
**COALESCE() – Handling NULL Values**

**Goal:** Learn how to replace `NULL` values with meaningful default values using the `COALESCE()` function.

---

## 💖 A Little Message for Today
Missing values are common in real-world databases. Instead of letting them make your reports confusing, you'll learn how to present clean and readable results.

---

## 📚 Quick Revision
`COALESCE()` returns the first non-NULL value from the list of expressions.

Example:
```sql
SELECT employee_name,
       COALESCE(phone_number, 'Not Available') AS phone_number
FROM employees;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display a nullable column and replace `NULL` values with **'Not Available'** using `COALESCE()`.

### Mission 2 (Easy)
Display all customers and replace missing email addresses (or another nullable column) with **'No Email'**.

### Mission 3 (Easy+)
Display products and replace missing descriptions (or another nullable column) with **'No Description'**.

### Mission 4 (Medium)
Use `LEFT JOIN` and `COALESCE()` to display related information, replacing missing values with a meaningful label.

### Mission 5 (Challenge)
Create a report that replaces every missing value from a chosen nullable column with a suitable default value while displaying all records.

---

## 🏆 Bonus Challenge
Display the total number of missing and non-missing values in a nullable column, replacing missing values with a readable label in the output.

---

## 💡 SQL Tip of the Day
`COALESCE()` is useful for creating clean reports because it prevents `NULL` values from appearing in the final result.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll combine `CASE`, `NULL`, and `COALESCE()` to build smarter SQL reports.

---

## 📝 Git Commit Message
`Completed Day 64 SQL Mission`

---

## 🎉 Closing Note
Excellent progress! You're learning how to make SQL reports more user-friendly and professional. Keep practising, and every new concept will become another powerful tool in your SQL toolkit.
