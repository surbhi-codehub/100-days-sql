
# 🌸 100 Days SQL Journey
## Day 97

## 🌼 Today's Topic
**Building a Complete Relational Database**

**Goal:** Learn how to design and build a complete relational database by combining tables, relationships, constraints, and sample data.

---

## 💖 A Little Message for Today

You're bringing together everything you've learned so far. A well-designed database isn't just a collection of tables—it's a structured system where data is accurate, connected, and easy to query.

---

## 📚 Quick Revision

A complete relational database typically includes:

- Multiple related tables
- PRIMARY KEY constraints
- FOREIGN KEY relationships
- NOT NULL, UNIQUE, and CHECK constraints
- Sample data for testing
- Queries to verify relationships

Example:

```sql
CREATE TABLE departments (
    department_id INTEGER PRIMARY KEY,
    department_name TEXT NOT NULL UNIQUE
);

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

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Design a `departments` table with appropriate constraints.

### Mission 2 (Easy)
Design an `employees` table related to `departments` using a `FOREIGN KEY`.

### Mission 3 (Easy+)
Create `customers` and `orders` tables with a relationship between them.

### Mission 4 (Medium)
Insert valid sample records into all tables and verify that relationships work correctly using `JOIN` queries.

### Mission 5 (Challenge)
Build a small database containing at least four related tables. Apply suitable constraints and write queries to retrieve meaningful business information.

---

## 🏆 Bonus Challenge

Create an ER diagram (on paper or using any diagram tool) for your database showing all tables, primary keys, foreign keys, and relationships. Then write one query that joins all related tables.

---

## 💡 SQL Tip of the Day

Design your database before writing SQL. A good schema makes queries simpler, improves data quality, and reduces future maintenance.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll build a mini SQL project by creating tables, inserting data, and writing analytical queries from start to finish.

---

## 📝 Git Commit Message

`Completed Day 97 SQL Mission`

---

## 🎉 Closing Note

Fantastic work! You're now applying everything you've learned to build a complete relational database. This is exactly the kind of practical experience that prepares you for real-world SQL projects and interviews.
