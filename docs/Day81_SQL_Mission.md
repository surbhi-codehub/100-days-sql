
# 🌸 100 Days SQL Journey
## Day 81

## 🌼 Today's Topic
**Date Arithmetic – Calculating Differences Between Dates**

**Goal:** Learn how to calculate the difference between two dates and use date arithmetic for practical business analysis.

---

## 💖 A Little Message for Today
Dates tell stories. By calculating the time between events, you can measure employee experience, customer activity, and order timelines. This is a key skill in reporting and analytics.

---

## 📚 Quick Revision

Many SQL databases provide functions to calculate date differences.

Common examples:
- `DATEDIFF()`
- Date subtraction (`date2 - date1`)
- `JULIANDAY()` (SQLite)

Example:

```sql
SELECT
    employee_id,
    hire_date,
    CURRENT_DATE AS today
FROM employees;
```

> The exact syntax for calculating date differences depends on the database system.

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display all employees with their `hire_date`.

### Mission 2 (Easy)
Display all orders along with their `order_date`, sorted from newest to oldest.

### Mission 3 (Easy+)
Calculate how many days have passed since each order was placed using your database's date functions.

### Mission 4 (Medium)
Create a report showing each employee and the number of years (or days) since they were hired.

### Mission 5 (Challenge)
Find the oldest order in the `orders` table and calculate how many days have passed since it was placed.

---

## 🏆 Bonus Challenge

Create a report showing:
- Employee Name
- Hire Date
- Approximate Years of Service

Sort the results by the longest-serving employee first.

---

## 💡 SQL Tip of the Day

Always use date data types and built-in date functions instead of treating dates as plain text. This makes calculations accurate and efficient.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to group records by month and year to create time-based summary reports.

---

## 📝 Git Commit Message

`Completed Day 81 SQL Mission`

---

## 🎉 Closing Note

Fantastic work! You're learning how to turn raw dates into meaningful insights. Date calculations are widely used in dashboards, business intelligence, and real-world SQL projects.
