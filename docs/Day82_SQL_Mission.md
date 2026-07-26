
# 🌸 100 Days SQL Journey
## Day 82

## 🌼 Today's Topic
**Grouping Data by Month and Year**

**Goal:** Learn how to group records by month and year to create meaningful time-based summary reports.

---

## 💖 A Little Message for Today
Business decisions often rely on trends over time rather than individual records. Grouping data by month and year helps uncover those trends.

---

## 📚 Quick Revision

You can extract parts of a date and combine them with `GROUP BY` to summarise data.

Example:

```sql
SELECT
    EXTRACT(YEAR FROM order_date) AS order_year,
    EXTRACT(MONTH FROM order_date) AS order_month,
    COUNT(*) AS total_orders
FROM orders
GROUP BY
    EXTRACT(YEAR FROM order_date),
    EXTRACT(MONTH FROM order_date)
ORDER BY order_year, order_month;
```

> Depending on your database, you may use `YEAR()`, `MONTH()`, or `strftime()` instead of `EXTRACT()`.

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display the total number of orders placed in each year.

### Mission 2 (Easy)
Display the total number of orders placed in each month.

### Mission 3 (Easy+)
Display the number of employees hired in each year.

### Mission 4 (Medium)
Create a report showing the total quantity ordered for each month.

### Mission 5 (Challenge)
Create a report showing the number of orders grouped by both year and month, sorted chronologically.

---

## 🏆 Bonus Challenge

Create a report displaying:
- Year
- Month
- Total Orders
- Total Quantity Ordered

Sort the report by year and month.

---

## 💡 SQL Tip of the Day

Combining date extraction functions with `GROUP BY` is one of the most common techniques used in business reporting and dashboards.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to use Common Table Expressions (CTEs) to write cleaner and more readable SQL queries.

---

## 📝 Git Commit Message

`Completed Day 82 SQL Mission`

---

## 🎉 Closing Note

Excellent work! You're now using dates to discover patterns and trends in your data. This is a fundamental skill for data analysis and reporting.
