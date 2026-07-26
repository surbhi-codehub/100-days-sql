
# 🌸 100 Days SQL Journey
## Day 92

## 🌼 Today's Topic
**ACID Properties of Transactions**

**Goal:** Learn the four ACID properties that make database transactions reliable and ensure data consistency.

---

## 💖 A Little Message for Today

Every modern database depends on ACID properties to keep data accurate and trustworthy. Whether you're transferring money, placing an order, or updating inventory, ACID ensures your data remains consistent even if something goes wrong.

---

## 📚 Quick Revision

**ACID** stands for:

- **Atomicity** – A transaction is completed entirely or not at all.
- **Consistency** – A transaction moves the database from one valid state to another.
- **Isolation** – Transactions do not interfere with each other while running.
- **Durability** – Once a transaction is committed, the changes are permanently saved.

Example:

```sql
BEGIN;

UPDATE accounts
SET balance = balance - 500
WHERE account_id = 1;

UPDATE accounts
SET balance = balance + 500
WHERE account_id = 2;

COMMIT;
```

If any statement fails, use:

```sql
ROLLBACK;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Explain the meaning of **Atomicity** in your own words.

### Mission 2 (Easy)
Write a transaction where two `UPDATE` statements are committed together and identify which ACID property ensures both succeed or fail together.

### Mission 3 (Easy+)
Give one practical example where **Consistency** protects data integrity.

### Mission 4 (Medium)
Describe a scenario where **Isolation** prevents problems when two users update the same data simultaneously.

### Mission 5 (Challenge)
Explain how **Durability** protects committed data after a database restart or unexpected system failure.

---

## 🏆 Bonus Challenge

Create a table with the following columns:

- ACID Property
- Meaning
- Real-World Example

Fill in one example for each property.

---

## 💡 SQL Tip of the Day

Transactions and ACID work together. A transaction defines *what* changes should happen, while ACID guarantees *how* those changes are handled safely.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn about SQL constraints, including `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, `NOT NULL`, and `CHECK`.

---

## 📝 Git Commit Message

`Completed Day 92 SQL Mission`

---

## 🎉 Closing Note

Fantastic work! Understanding ACID is a major milestone in database learning. These principles are the foundation of reliable applications and are frequently discussed in SQL and Data Engineering interviews.
