
# 🌸 100 Days SQL Journey
## Day 80

## 🌼 Today's Topic
**Extracting Year, Month, and Day from Dates**

**Goal:** Learn how to extract individual parts of a date, such as the year, month, and day, for reporting and analysis.

---

## 💖 A Little Message for Today
Dates contain valuable information beyond just the full date. Being able to separate the year, month, or day helps answer business questions like "How many orders were placed this month?" or "Which year had the most hires?"

---

## 📚 Quick Revision

Many SQL databases provide functions to extract parts of a date.

Common examples:
- `EXTRACT(YEAR FROM date_column)`
- `EXTRACT(MONTH FROM date_column)`
- `EXTRACT(DAY FROM date_column)`

Example:

```sql
SELECT
    order_id,
    order_date,
    EXTRACT(YEAR FROM order_date) AS order_year,
    EXTRACT(MONTH FROM order_date) AS order_month,
    EXTRACT(DAY FROM order_date) AS order_day
FROM orders;
```

> The exact function name may differ depending on the database system (for example, `YEAR()`, `MONTH()`, or `DAY()`).

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display every employee along with the year they were hired.

### Mission 2 (Easy)
Display every order along with its month.

### Mission 3 (Easy+)
Display every order with separate columns for year, month, and day.

### Mission 4 (Medium)
Count how many employees were hired in each year.

### Mission 5 (Challenge)
Create a report showing the total number of orders placed in each month, sorted by month.

---

## 🏆 Bonus Challenge

Create a report displaying:
- Employee Name
- Hire Date
- Hire Year
- Hire Month

Sort the results by hire year and then hire month.

---

## 💡 SQL Tip of the Day

Extracting date parts is useful for grouping, filtering, and creating monthly or yearly business reports.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to calculate the difference between two dates using SQL date arithmetic.

---

## 📝 Git Commit Message

`Completed Day 80 SQL Mission`

---

## 🎉 Closing Note

Congratulations on reaching Day 80! You're now working with one of the most important aspects of data analysis—date-based reporting. Keep practising, and you'll soon be analysing trends with confidence.
