
# 🌸 100 Days SQL Journey
## Day 65

## 🌼 Today's Topic
**CASE + COALESCE() + NULL – Practical Reports**

**Goal:** Learn how to combine `CASE`, `COALESCE()`, and `NULL` handling to create clean, user-friendly SQL reports.

---

## 💖 A Little Message for Today
You're now combining multiple SQL concepts to solve real-world problems. Keep practising one step at a time, and you'll soon write queries that are both powerful and easy to understand.

---

## 📚 Quick Revision
- `CASE` adds conditional logic.
- `COALESCE()` replaces `NULL` values.
- `IS NULL` and `IS NOT NULL` help identify missing data.

Example:
```sql
SELECT employee_name,
       CASE
           WHEN COALESCE(phone_number, '') = '' THEN 'No Contact'
           ELSE 'Contact Available'
       END AS contact_status
FROM employees;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display a nullable column and replace missing values using `COALESCE()`.

### Mission 2 (Easy)
Use `CASE` to label rows as **Available** or **Missing** based on whether a nullable column contains `NULL`.

### Mission 3 (Easy+)
Display all customers (or another suitable table) and replace missing values with readable text using `COALESCE()`.

### Mission 4 (Medium)
Use `LEFT JOIN` together with `COALESCE()` to display related information, showing a default value when no matching record exists.

### Mission 5 (Challenge)
Create a report that uses both `CASE` and `COALESCE()` to categorise records and replace missing values in the same query.

---

## 🏆 Bonus Challenge
Build a report that counts records with missing values and labels each record using `CASE`.

---

## 💡 SQL Tip of the Day
Using `CASE` together with `COALESCE()` makes reports much easier for users to read because they see meaningful labels instead of `NULL`.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll begin learning the `UNION` operator to combine results from multiple queries.

---

## 📝 Git Commit Message
`Completed Day 65 SQL Mission`

---

## 🎉 Closing Note
Fantastic work! You're combining multiple SQL concepts like a real data professional. Keep practising consistently, and each new topic will feel more natural than the last.
