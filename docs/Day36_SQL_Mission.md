
# 🌸 100 Days SQL Journey
## Day 36

## 🌼 Today's Topic
**MIN() Function**

**Goal:** Learn how to find the smallest value in a numeric or date column using `MIN()`.

---

## 💖 A Little Message for Today
Learning SQL is like solving small puzzles. Every query you finish makes the next one a little easier. Keep going—your consistency is your greatest strength.

---

## 📚 Quick Revision
The `MIN()` function returns the smallest value from a column.
It can be used with numbers, dates, and even text (alphabetically).

Example:
```sql
SELECT MIN(price)
FROM products;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Find the lowest product price in the `products` table.

### Mission 2 (Easy)
Find the minimum salary among all employees.

### Mission 3 (Easy+)
Find the earliest `order_date` in the `orders` table.

### Mission 4 (Medium)
Find the minimum stock quantity for products in the **Electronics** category.

### Mission 5 (Challenge)
Find the earliest hire date of employees whose `department_id` is 3.

---

## 🏆 Bonus Challenge
Find the smallest order quantity that is greater than 1.

---

## 💡 SQL Tip of the Day
`MIN()` ignores `NULL` values automatically, so only valid values are considered.

---

## 🌱 Tomorrow's Preview
Tomorrow you'll discover how to find the largest value using the `MAX()` function.

---

## 📝 Git Commit Message
`Completed Day 36 SQL Mission`

---

## 🎉 Closing Note
You're adding another valuable SQL skill to your toolkit. Stay curious, keep practising, and enjoy watching your confidence grow with every mission.
