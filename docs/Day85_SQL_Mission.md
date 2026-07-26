
# 🌸 100 Days SQL Journey
## Day 85

## 🌼 Today's Topic
**Recursive Common Table Expressions (Recursive CTEs)**

**Goal:** Learn how Recursive CTEs repeatedly execute a query to work with hierarchical data and generate sequences.

---

## 💖 A Little Message for Today

You're entering one of SQL's advanced features. Recursive CTEs may seem challenging at first, but once you understand the pattern, they become an excellent tool for solving hierarchical and recursive problems.

---

## 📚 Quick Revision

A Recursive CTE consists of two parts:

- **Anchor Query** – Produces the starting rows.
- **Recursive Query** – Refers back to the CTE and continues until no more rows are produced.

Example:

```sql
WITH RECURSIVE Numbers AS (
    SELECT 1 AS num
    UNION ALL
    SELECT num + 1
    FROM Numbers
    WHERE num < 10
)
SELECT *
FROM Numbers;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Create a Recursive CTE that generates numbers from **1 to 10**.

### Mission 2 (Easy)
Modify the Recursive CTE to generate numbers from **1 to 20**.

### Mission 3 (Easy+)
Generate even numbers from **2 to 20** using a Recursive CTE.

### Mission 4 (Medium)
Generate a sequence of dates starting from a chosen date for the next **7 days** using a Recursive CTE.

### Mission 5 (Challenge)
Suppose an employee table contains `employee_id` and `manager_id`. Write a Recursive CTE that displays the reporting hierarchy starting from a chosen manager.

---

## 🏆 Bonus Challenge

Create a Recursive CTE that generates the multiplication table of **5** from **5 × 1** through **5 × 10**.

---

## 💡 SQL Tip of the Day

Recursive CTEs are commonly used for organisational hierarchies, folder structures, bill-of-materials reports, calendars, and sequence generation.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn how to use SQL Views to save complex queries as reusable virtual tables.

---

## 📝 Git Commit Message

`Completed Day 85 SQL Mission`

---

## 🎉 Closing Note

Fantastic work! Recursive CTEs are a major milestone in SQL. Even if they feel difficult initially, consistent practice will help you master one of the most powerful querying techniques.
