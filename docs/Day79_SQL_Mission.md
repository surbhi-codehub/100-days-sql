
# 🌸 100 Days SQL Journey
## Day 79

## 🌼 Today's Topic
**SQL Date & Time Functions – Introduction**

**Goal:** Learn how to work with dates and time values using common SQL date functions.

---

## 💖 A Little Message for Today
Dates are everywhere in databases—from customer registrations to employee hiring and order history. Understanding date functions will help you analyse trends and build meaningful reports.

---

## 📚 Quick Revision

Date functions help retrieve or manipulate date values.

Common examples:
- `CURRENT_DATE` – Returns today's date.
- `CURRENT_TIMESTAMP` – Returns the current date and time.

Example:

```sql
SELECT CURRENT_DATE;
```

Example:

```sql
SELECT order_id, order_date
FROM orders
WHERE order_date < CURRENT_DATE;
```

> Date function names can vary slightly between database systems.

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display all orders with their `order_date`.

### Mission 2 (Easy)
Display all employees along with their `hire_date`.

### Mission 3 (Easy+)
Display all orders placed before today's date.

### Mission 4 (Medium)
Sort all employees by `hire_date`, showing the earliest hires first.

### Mission 5 (Challenge)
Create a report showing customer orders sorted by the most recent `order_date`.

---

## 🏆 Bonus Challenge

Write a query to display today's date using your database's built-in date function, then compare it with the dates stored in the `orders` table.

---

## 💡 SQL Tip of the Day

Store dates using proper date data types instead of text. It makes filtering, sorting, and calculations much easier.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to extract parts of a date, such as the year, month, and day.

---

## 📝 Git Commit Message

`Completed Day 79 SQL Mission`

---

## 🎉 Closing Note

Great job! Date functions are essential for analysing business data. As you continue, you'll learn how to break dates into useful components and perform powerful date-based analysis.
