
# 🌸 100 Days SQL Journey
## Day 93

## 🌼 Today's Topic
**SQL Constraints – Introduction**

**Goal:** Learn how SQL constraints enforce rules to maintain accurate, valid, and consistent data.

---

## 💖 A Little Message for Today

A database is only as good as the quality of the data it stores. Constraints help prevent invalid information from entering your tables, making your applications more reliable.

---

## 📚 Quick Revision

Common SQL constraints:

- **PRIMARY KEY** – Uniquely identifies each row.
- **FOREIGN KEY** – Maintains relationships between tables.
- **NOT NULL** – Prevents empty values.
- **UNIQUE** – Prevents duplicate values.
- **CHECK** – Restricts values based on a condition.

Example:

```sql
CREATE TABLE employees (
    employee_id INTEGER PRIMARY KEY,
    first_name TEXT NOT NULL,
    email TEXT UNIQUE,
    salary REAL CHECK (salary > 0),
    department_id INTEGER
);
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Create a table with a `PRIMARY KEY` column.

### Mission 2 (Easy)
Create a table where `first_name` cannot contain `NULL` values using `NOT NULL`.

### Mission 3 (Easy+)
Create a table where the `email` column must contain unique values using `UNIQUE`.

### Mission 4 (Medium)
Create a table with a `CHECK` constraint to ensure `salary` is greater than zero.

### Mission 5 (Challenge)
Create two related tables using `PRIMARY KEY` and `FOREIGN KEY`, then insert sample data that follows the relationship.

---

## 🏆 Bonus Challenge

Design a `students` table containing:
- `student_id` (PRIMARY KEY)
- `name` (NOT NULL)
- `email` (UNIQUE)
- `age` (CHECK age >= 18)

Write the `CREATE TABLE` statement with all constraints.

---

## 💡 SQL Tip of the Day

Constraints enforce data quality at the database level, helping prevent invalid data even if an application makes a mistake.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll explore each constraint in more detail, starting with `PRIMARY KEY` and `FOREIGN KEY`.

---

## 📝 Git Commit Message

`Completed Day 93 SQL Mission`

---

## 🎉 Closing Note

Excellent work! Constraints are essential for designing robust databases. By enforcing rules directly in the database, you'll build systems that are more accurate, secure, and easier to maintain.
