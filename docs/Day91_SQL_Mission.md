
# 🌸 100 Days SQL Journey
## Day 91

## 🌼 Today's Topic
**SQL Transactions – BEGIN, COMMIT, and ROLLBACK**

**Goal:** Learn how transactions ensure data integrity by grouping multiple SQL statements into a single unit of work.

---

## 💖 A Little Message for Today

Databases should always remain consistent. Transactions make sure that either every step of an operation succeeds or nothing changes at all. This is one of the foundations of reliable database systems.

---

## 📚 Quick Revision

A transaction controls how changes are saved.

- `BEGIN TRANSACTION` (or `BEGIN`) starts a transaction.
- `COMMIT` permanently saves all changes.
- `ROLLBACK` cancels all changes made since the transaction began.

Example:

```sql
BEGIN;

UPDATE products
SET stock_quantity = stock_quantity - 1
WHERE product_id = 101;

COMMIT;
```

If something goes wrong:

```sql
BEGIN;

UPDATE products
SET stock_quantity = stock_quantity - 1
WHERE product_id = 101;

ROLLBACK;
```

---

# 🎯 Today's SQL Missions

### Mission 1 (Very Easy)
Start a transaction using `BEGIN`.

### Mission 2 (Easy)
Update a customer's city inside a transaction and save the change using `COMMIT`.

### Mission 3 (Easy+)
Update an employee's salary inside a transaction, then cancel the change using `ROLLBACK`.

### Mission 4 (Medium)
Within a single transaction, update two different rows in the `products` table and commit both changes together.

### Mission 5 (Challenge)
Simulate placing an order by updating `orders` and reducing `products.stock_quantity` inside one transaction. Commit only after both statements execute successfully.

---

## 🏆 Bonus Challenge

Create a transaction that performs multiple updates. Before committing, verify the changes using a `SELECT` query. Then either `COMMIT` or `ROLLBACK` depending on the result.

---

## 💡 SQL Tip of the Day

Transactions help maintain data integrity. Use them whenever multiple related changes must succeed or fail together.

---

## 🌱 Tomorrow's Preview

Tomorrow you'll learn about the ACID properties that make database transactions reliable.

---

## 📝 Git Commit Message

`Completed Day 91 SQL Mission`

---

## 🎉 Closing Note

Excellent work! Transactions are a core database concept used in banking, e-commerce, inventory systems, and countless other real-world applications. Mastering them is a big step toward becoming a professional SQL developer.
