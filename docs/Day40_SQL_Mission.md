
# 🌸 100 Days SQL Journey
## Day 40

## 🌼 Today's Topic
**Aggregate Functions – Final Practice**

**Goal:** Reinforce everything you've learned about `COUNT()`, `SUM()`, `AVG()`, `MIN()`, and `MAX()` before moving on to `GROUP BY`.

---

## 💖 A Little Message for Today
You've come a long way in just 40 days. Every query you've written has strengthened your logical thinking. Keep building one step at a time—consistency always wins.

---

## 📚 Quick Revision
Aggregate functions summarize data into meaningful results.

Common aggregate functions:
- `COUNT()` → Counts rows
- `SUM()` → Adds values
- `AVG()` → Finds the average
- `MIN()` → Finds the smallest value
- `MAX()` → Finds the largest value

Example:
```sql
SELECT COUNT(*), SUM(quantity), AVG(quantity), MIN(quantity), MAX(quantity)
FROM orders;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display the total number of employees and the highest salary.

### Mission 2 (Easy)
Find the total stock quantity and the average product price from the `products` table.

### Mission 3 (Easy+)
Display the total number of orders, the minimum quantity, and the maximum quantity ordered.

### Mission 4 (Medium)
For products in the **Electronics** category, display the total number of products, total stock quantity, average price, lowest price, and highest price.

### Mission 5 (Challenge)
For employees whose `department_id` is 3, display the total number of employees, total salary, average salary, minimum salary, and maximum salary in one query.

---

## 🏆 Bonus Challenge
Write a single query that summarizes the `orders` table by displaying the total number of orders, total ordered quantity, average quantity, smallest quantity, and largest quantity.

---

## 💡 SQL Tip of the Day
When you need a quick overview of data, aggregate functions are your best friend. They help you summarize thousands of rows with a single query.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll begin **GROUP BY**, one of the most powerful SQL features for analysing data by categories.

---

## 📝 Git Commit Message
`Completed Day 40 SQL Mission`

---

## 🎉 Closing Note
Congratulations on completing the Aggregate Functions module! You now have a strong foundation for real-world SQL analysis. Keep practising, stay curious, and get ready for the exciting journey into `GROUP BY`.
