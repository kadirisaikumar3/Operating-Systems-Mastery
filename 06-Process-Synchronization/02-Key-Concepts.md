# 02-Key-Concepts
# 🔑 Key Concepts

Understanding these concepts is essential before learning synchronization algorithms.

---

# Critical Section

A Critical Section is the portion of code where shared resources are accessed.

Only one process should execute inside the Critical Section at a time.

Example

```

balance = balance - amount;

```

---

# Race Condition

A Race Condition occurs when multiple processes access and modify shared data simultaneously, leading to unpredictable results.

Example

Two ATM withdrawals happening at the same time.

---

# Mutual Exclusion

Mutual Exclusion ensures that only one process enters the Critical Section at any given time.

---

# Synchronization Requirements

A good synchronization solution should satisfy:

- Mutual Exclusion
- Progress
- Bounded Waiting

---

# Semaphore

A synchronization tool used to control access to shared resources.

Types

- Binary Semaphore
- Counting Semaphore

---

# Mutex

Mutex stands for **Mutual Exclusion**.

Only the thread that locks the mutex can unlock it.

---

# Monitor

A high-level synchronization construct that combines shared data with procedures.

Programming languages like Java provide monitor support using the `synchronized` keyword.

---

# Peterson's Solution

A software-based solution for synchronizing two processes.

Requirements:

- Two processes
- Shared variables
- Busy waiting

---

# Synchronization Tools

```

Process

↓

Critical Section

↓

Semaphore / Mutex / Monitor

↓

Shared Resource

```

---

# Frequently Asked

- Critical Section Problem
- Race Condition
- Mutual Exclusion
- Semaphore vs Mutex
- Monitor
- Peterson's Solution

---

# Summary

Understanding these concepts makes solving synchronization problems much easier.