
# 🌸 100 Days SQL Journey
## Day 54

## 🌼 Today's Topic
**LEFT JOIN – Advanced Practice**

**Goal:** Build confidence in using `LEFT JOIN` to create complete business reports that include records with and without matching data.

---

## 💖 A Little Message for Today
Every report you build teaches you something new about data. Stay patient, keep experimenting, and remember that consistent practice always leads to lasting confidence.

---

## 📚 Quick Revision
A `LEFT JOIN` keeps every row from the left table.
If a matching row doesn't exist in the right table, SQL returns `NULL` for the right table's columns.

Example:
```sql
SELECT p.product_name,
       o.order_id
FROM products p
LEFT JOIN orders o
ON p.product_id = o.product_id;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Display every customer along with their latest order details. Include customers who have never placed an order.

### Mission 2 (Easy)
Display every department with the total number of employees. Include departments that currently have no employees.

### Mission 3 (Easy+)
Display every supplier with the total stock quantity of the products they supply. Include suppliers without any products.

### Mission 4 (Medium)
Display every product together with the total quantity ordered. Include products that have never been ordered.

### Mission 5 (Challenge)
Display every customer with the total number of orders and the average order quantity. Customers without orders should also appear in the result.

---

## 🏆 Bonus Challenge
Display every department with the minimum, maximum, and average salary of its employees. Departments without employees should still be included.

---

## 💡 SQL Tip of the Day
When using `LEFT JOIN`, check for `NULL` values in the joined table to identify records that don't have matching data.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll complete the final `LEFT JOIN` practice before moving on to subqueries.

---

## 📝 Git Commit Message
`Completed Day 54 SQL Mission`

---

## 🎉 Closing Note
You're becoming skilled at creating complete reports from related tables. Keep practising, and you'll soon be ready for even more advanced SQL techniques.
