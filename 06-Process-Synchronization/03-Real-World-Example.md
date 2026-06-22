# 🌍 Real-World Examples

Process Synchronization is used whenever multiple processes or threads access shared resources. Without synchronization, inconsistent results, crashes, and data corruption can occur.

---

# Example 1: ATM Banking System

Suppose two customers use different ATMs to withdraw money from the same account.

Account Balance

₹10,000

Customer A withdraws ₹4,000

Customer B withdraws ₹5,000

Without synchronization:

Both ATMs may read the balance as ₹10,000 simultaneously.

Incorrect Final Balance

₹6,000 or ₹5,000

Correct Final Balance

₹1,000

Synchronization prevents this race condition.

---

# Example 2: Railway Reservation

Two users book the last available seat simultaneously.

Without synchronization:

Both users may receive the same seat number.

With synchronization:

Only one booking succeeds.

---

# Example 3: Google Docs

Multiple users edit the same document.

Synchronization ensures:

- No data loss
- Proper update ordering
- Consistent document state

---

# Example 4: Online Shopping

Only one laptop remains in stock.

Two customers click "Buy Now" simultaneously.

Synchronization prevents selling the same product twice.

---

# Example 5: Database Transactions

Banking databases synchronize transactions to ensure:

- Data consistency
- Atomicity
- Isolation

---

# Example 6: Printer Queue

Several users send print requests.

Synchronization ensures:

- One print job executes at a time.
- Print order remains correct.

---

# Interview Insight

Question

Where is synchronization used in real life?

Answer

- Banking
- Ticket Booking
- Database Systems
- Operating Systems
- Cloud Computing
- Multiplayer Games

---

# Key Takeaways

Synchronization protects shared resources from concurrent access.