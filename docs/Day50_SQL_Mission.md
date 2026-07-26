
# 🌸 100 Days SQL Journey
## Day 50

## 🌼 Today's Topic
**INNER JOIN – Final Practice**

**Goal:** Strengthen your understanding of `INNER JOIN` by solving practical business scenarios involving multiple related tables.

---

## 💖 A Little Message for Today
You've reached an exciting milestone—Day 50! Halfway through the journey, you've already built a strong SQL foundation. Keep learning one query at a time, and your confidence will continue to grow.

---

## 📚 Quick Revision
`INNER JOIN` combines rows from two or more tables when the join condition matches.

Example:
```sql
SELECT c.customer_name,
       o.order_id,
       p.product_name
FROM orders o
INNER JOIN customers c
    ON o.customer_id = c.customer_id
INNER JOIN products p
    ON o.product_id = p.product_id;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display each employee along with the department name.

### Mission 2 (Easy)
Display each order together with the customer name.

### Mission 3 (Easy+)
Display each order with the customer name and product name.

### Mission 4 (Medium)
Display each supplier along with the products supplied by them.

### Mission 5 (Challenge)
Using `INNER JOIN` and `GROUP BY`, display each customer with the total number of orders and the total quantity ordered.

---

## 🏆 Bonus Challenge
Display each department along with the number of employees working in it.

---

## 💡 SQL Tip of the Day
When joining multiple tables, always qualify column names with table aliases to avoid ambiguity and improve readability.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll begin learning **LEFT JOIN** and discover how to include rows that don't have matching records.

---

## 📝 Git Commit Message
`Completed Day 50 SQL Mission`

---

## 🎉 Closing Note
Congratulations on completing the first 50 days! You've developed valuable SQL skills that form the backbone of data analysis. Stay consistent—the next 50 days will unlock even more powerful techniques.
