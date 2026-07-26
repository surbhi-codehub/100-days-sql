
# 🌸 100 Days SQL Journey
## Day 96

## 🌼 Today's Topic
**Designing Tables with Multiple Constraints**

**Goal:** Learn how to combine multiple SQL constraints to build complete, reliable database tables.

---

## 💖 A Little Message for Today

Professional database design is about preventing bad data before it reaches your application. By combining constraints, you can create tables that are both flexible and dependable.

---

## 📚 Quick Revision

A table can contain several constraints at the same time.

Example:

```sql
CREATE TABLE employees (
    employee_id INTEGER PRIMARY KEY,
    first_name TEXT NOT NULL,
    email TEXT UNIQUE,
    salary REAL CHECK (salary > 0),
    department_id INTEGER,
    FOREIGN KEY (department_id)
        REFERENCES departments(department_id)
);
```

This table uses:
- PRIMARY KEY
- NOT NULL
- UNIQUE
- CHECK
- FOREIGN KEY

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Create a `departments` table with a `PRIMARY KEY` and a `NOT NULL` department name.

### Mission 2 (Easy)
Create an `employees` table using `PRIMARY KEY`, `NOT NULL`, `UNIQUE`, and `CHECK`.

### Mission 3 (Easy+)
Add a `FOREIGN KEY` to connect `employees.department_id` with `departments.department_id`.

### Mission 4 (Medium)
Insert valid sample records into both tables and verify that all constraints allow the inserts.

### Mission 5 (Challenge)
Attempt to insert records that violate each constraint (duplicate value, NULL value, invalid foreign key, and invalid CHECK value). Observe which statements fail and explain why.

---

## 🏆 Bonus Challenge

Design a simple **Library Management** database with:

- `authors`
- `books`

Apply:
- `PRIMARY KEY`
- `FOREIGN KEY`
- `NOT NULL`
- `UNIQUE`
- `CHECK`

Insert a few valid records to test your design.

---

## 💡 SQL Tip of the Day

The best database designs enforce business rules using constraints instead of relying only on application code.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll build a complete relational database by combining tables, relationships, constraints, and sample data.

---

## 📝 Git Commit Message

`Completed Day 96 SQL Mission`

---

## 🎉 Closing Note

Outstanding work! You're now designing tables the way professional database developers do. Combining multiple constraints is a key step toward building secure, consistent, and production-ready databases.
