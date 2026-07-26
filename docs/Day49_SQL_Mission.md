
# 🌸 100 Days SQL Journey
## Day 49

## 🌼 Today's Topic
**INNER JOIN with Multiple Tables**

**Goal:** Learn how to retrieve related information by joining more than two tables using `INNER JOIN`.

---

## 💖 A Little Message for Today
Every join you write helps you see how real-world data is connected. Stay curious, experiment with different queries, and enjoy the learning process.

---

## 📚 Quick Revision
`INNER JOIN` combines rows that have matching values in related tables.
You can join multiple tables by adding more `INNER JOIN` clauses.

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
Display each order along with the customer name.

### Mission 2 (Easy)
Display each product together with its supplier name.

### Mission 3 (Easy+)
Display each employee along with the department name.

### Mission 4 (Medium)
Display each order with the customer name and product name.

### Mission 5 (Challenge)
Display each customer with the total number of orders placed using `INNER JOIN` and `GROUP BY`.

---

## 🏆 Bonus Challenge
Display each department along with the average salary of its employees.

---

## 💡 SQL Tip of the Day
Use short table aliases like `c`, `o`, and `p` to make JOIN queries easier to read.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll explore `LEFT JOIN` and learn how to include unmatched rows.

---

## 📝 Git Commit Message
`Completed Day 49 SQL Mission`

---

## 🎉 Closing Note
You're now connecting data from multiple tables like a real SQL developer. Keep practising, and joins will soon become second nature.
