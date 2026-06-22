# 01-Concepts
# 🔒 Deadlock Concepts

## What is Deadlock?

A Deadlock is a condition where two or more processes wait indefinitely for resources held by each other.

As a result,

- No process can continue.
- CPU may remain idle.
- System throughput decreases.

---

## Definition

> A Deadlock is a permanent blocking situation in which every process waits for an event that can only be caused by another waiting process.

---

# Example

Imagine two people:

Person A has Book 1.

Person B has Book 2.

A wants Book 2.

B wants Book 1.

Neither releases their book.

Both wait forever.

This is a Deadlock.

---

# Operating System Example

Thread A

Locks Printer

↓

Needs Scanner

Thread B

Locks Scanner

↓

Needs Printer

Both wait forever.

---

# Why Deadlocks Occur?

Deadlocks occur because processes compete for limited resources.

Examples

- Printer
- Scanner
- Database Lock
- Memory
- Files

---

# Characteristics

- Permanent Blocking
- Circular Waiting
- Resource Dependency
- No Progress

---

# Real-World Examples

- ATM Systems
- Railway Reservation
- Database Transactions
- Cloud Computing
- Operating Systems

---

# Google Interview Tip

Deadlock questions usually begin with

"Suppose Process A owns Resource X..."

Immediately think of

- Coffman Conditions
- Resource Allocation Graph
- Prevention

---

# Key Takeaways

- Deadlock blocks execution.
- Resources are shared.
- Prevention is better than recovery.