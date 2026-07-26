
# 🌸 100 Days SQL Journey
## Day 95

## 🌼 Today's Topic
**UNIQUE, NOT NULL & CHECK Constraints – Ensuring Data Quality**

**Goal:** Learn how the `UNIQUE`, `NOT NULL`, and `CHECK` constraints work together to maintain accurate and valid data.

---

## 💖 A Little Message for Today

A well-designed database doesn't just store data—it protects it. These constraints help prevent duplicate, missing, and invalid values before they enter your tables.

---

## 📚 Quick Revision

- **NOT NULL** – Prevents a column from storing `NULL`.
- **UNIQUE** – Prevents duplicate values.
- **CHECK** – Ensures values satisfy a condition.

Example:

```sql
CREATE TABLE employees (
    employee_id INTEGER PRIMARY KEY,
    first_name TEXT NOT NULL,
    email TEXT UNIQUE,
    salary REAL CHECK (salary > 0)
);
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Create a table where `first_name` cannot be `NULL`.

### Mission 2 (Easy)
Create a table where the `email` column must contain unique values.

### Mission 3 (Easy+)
Create a table where `salary` must always be greater than zero using a `CHECK` constraint.

### Mission 4 (Medium)
Create a `products` table with:
- `product_name` as `NOT NULL`
- `price` checked to be greater than zero
- `product_code` marked as `UNIQUE`

### Mission 5 (Challenge)
Create a `students` table with:
- `student_id` as `PRIMARY KEY`
- `name` as `NOT NULL`
- `email` as `UNIQUE`
- `age` checked to be at least 18

Insert both valid and invalid sample records and observe which statements succeed or fail.

---

## 🏆 Bonus Challenge

Design a `users` table containing:
- Username (`UNIQUE`)
- Password (`NOT NULL`)
- Age (`CHECK (age >= 13)`)

Test each constraint by attempting to insert invalid data.

---

## 💡 SQL Tip of the Day

Database constraints enforce rules automatically, helping protect data quality regardless of which application inserts the data.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to combine multiple constraints while designing complete database tables.

---

## 📝 Git Commit Message

`Completed Day 95 SQL Mission`

---

## 🎉 Closing Note

Excellent work! You're learning the rules that keep databases clean, reliable, and trustworthy. Mastering constraints will help you design professional-quality database schemas.
