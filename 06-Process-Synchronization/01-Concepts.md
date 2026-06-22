# 01-Concepts
# 🔄 Process Synchronization Concepts

## What is Process Synchronization?

Process Synchronization is the technique of coordinating multiple processes or threads so that they can safely access shared resources without causing inconsistent results.

Whenever two or more processes access the same shared data simultaneously, synchronization is required.

> **Definition**
>
> Process Synchronization is the process of controlling the execution order of concurrent processes to maintain data consistency and correctness.

---

# Why is Synchronization Needed?

Without synchronization:

- Race Conditions occur.
- Data becomes inconsistent.
- Shared variables may have incorrect values.
- Applications may crash.

Synchronization ensures only one process accesses the critical section at a time.

---

# Example

Suppose two users withdraw money from the same bank account simultaneously.

Initial Balance

₹10,000

User A withdraws ₹4,000

User B withdraws ₹5,000

Without synchronization,

Both processes may read the same balance.

Final balance becomes incorrect.

---

# Synchronization Flow

```

Process A

↓

Shared Resource

↑

Process B

```

Synchronization controls access to the shared resource.

---

# Goals

- Prevent Race Conditions
- Ensure Mutual Exclusion
- Maintain Data Consistency
- Improve Reliability
- Support Concurrent Execution

---

# Real-World Examples

- ATM Machines
- Online Banking
- Railway Reservation
- Ticket Booking
- Google Docs Collaboration
- Database Transactions

---

# Interview Tip

Most interview questions begin with:

"Suppose two threads update the same variable..."

The answer usually starts with:

Race Condition

↓

Critical Section

↓

Synchronization

---

# Key Takeaways

- Synchronization protects shared resources.
- Multiple processes require coordination.
- Synchronization improves correctness and reliability.