
# 🌸 100 Days SQL Journey
## Day 78

## 🌼 Today's Topic
**DISTINCT with Aggregate Functions**

**Goal:** Learn how to use `DISTINCT` with aggregate functions to calculate summaries based on unique values.

---

## 💖 A Little Message for Today
Not every duplicate should be counted. Sometimes you need to analyse only unique values to get meaningful insights. Today's lesson will help you do exactly that.

---

## 📚 Quick Revision

`DISTINCT` can be combined with aggregate functions such as `COUNT()` to work with unique values.

Example:

```sql
SELECT COUNT(DISTINCT city) AS unique_cities
FROM customers;
```

Another example:

```sql
SELECT COUNT(DISTINCT category) AS total_categories
FROM products;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Count the number of unique cities in the `customers` table.

### Mission 2 (Easy)
Count the number of unique job titles in the `employees` table.

### Mission 3 (Easy+)
Count the number of unique product categories in the `products` table.

### Mission 4 (Medium)
Count the number of unique customers who have placed orders using `COUNT(DISTINCT customer_id)`.

### Mission 5 (Challenge)
Create a report that displays the total number of unique cities, departments, and product categories using separate aggregate queries.

---

## 🏆 Bonus Challenge

Compare the output of:

```sql
COUNT(city)
```

and

```sql
COUNT(DISTINCT city)
```

Explain why the results are different.

---

## 💡 SQL Tip of the Day

`COUNT(DISTINCT column_name)` is one of the most commonly used aggregate expressions in reporting because it counts unique values instead of every row.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll begin learning SQL date and time functions for working with dates.

---

## 📝 Git Commit Message

`Completed Day 78 SQL Mission`

---

## 🎉 Closing Note

Fantastic work! You're learning how to create more accurate summaries by focusing on unique values. This technique is widely used in dashboards, analytics, and business reporting.
