
# 🌸 100 Days SQL Journey
## Day 94

## 🌼 Today's Topic
**PRIMARY KEY & FOREIGN KEY – Building Relationships**

**Goal:** Learn how `PRIMARY KEY` and `FOREIGN KEY` constraints uniquely identify records and create relationships between tables.

---

## 💖 A Little Message for Today

Relational databases are powerful because tables can work together. Primary and Foreign Keys are the foundation of those relationships and are essential for designing well-structured databases.

---

## 📚 Quick Revision

- **PRIMARY KEY** uniquely identifies each row in a table.
- **FOREIGN KEY** references a Primary Key in another table to maintain relationships.

Example:

```sql
CREATE TABLE departments (
    department_id INTEGER PRIMARY KEY,
    department_name TEXT NOT NULL
);

CREATE TABLE employees (
    employee_id INTEGER PRIMARY KEY,
    first_name TEXT,
    department_id INTEGER,
    FOREIGN KEY (department_id)
        REFERENCES departments(department_id)
);
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Create a `departments` table with `department_id` as the `PRIMARY KEY`.

### Mission 2 (Easy)
Create an `employees` table with `employee_id` as the `PRIMARY KEY`.

### Mission 3 (Easy+)
Add a `department_id` column to the `employees` table and define it as a `FOREIGN KEY` referencing `departments`.

### Mission 4 (Medium)
Insert sample data into both tables and write a query that joins them to display employee names with their department names.

### Mission 5 (Challenge)
Create `customers` and `orders` tables using a `PRIMARY KEY` and `FOREIGN KEY`. Insert sample data and display customer names along with their orders using an `INNER JOIN`.

---

## 🏆 Bonus Challenge

Design a simple database for a library with these tables:

- `authors`
- `books`

Use a `PRIMARY KEY` for each table and a `FOREIGN KEY` to connect books with their authors. Insert a few sample records and retrieve the data using a join.

---

## 💡 SQL Tip of the Day

Every table should normally have a Primary Key. Foreign Keys help maintain referential integrity by preventing invalid relationships between tables.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn about the `UNIQUE`, `NOT NULL`, and `CHECK` constraints in greater detail and discover how they improve data quality.

---

## 📝 Git Commit Message

`Completed Day 94 SQL Mission`

---

## 🎉 Closing Note

Fantastic work! You've learned the core building blocks of relational databases. Mastering Primary Keys and Foreign Keys will make it much easier to design reliable databases and write powerful SQL queries.
