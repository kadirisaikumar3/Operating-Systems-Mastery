# 06-Google-Interview-Corner
# 🚀 Google Interview Corner

Process Synchronization is among the most frequently asked topics in Operating System interviews.

---

# Question 1

What is Process Synchronization?

Expected Answer

Synchronization coordinates concurrent processes or threads accessing shared resources to maintain correctness and consistency.

---

# Question 2

What is Race Condition?

Expected Answer

A Race Condition occurs when multiple threads access and modify shared data simultaneously, producing unpredictable results.

---

# Question 3

How do you solve Race Conditions?

Expected Answer

Using:

- Mutex
- Semaphore
- Monitor
- synchronized (Java)
- Locks

---

# Question 4

Semaphore vs Mutex

| Semaphore | Mutex |
|-----------|-------|
| Integer Variable | Lock Object |
| Multiple Resources | Single Resource |
| acquire()/release() | lock()/unlock() |

---

# Question 5

Critical Section Requirements

- Mutual Exclusion
- Progress
- Bounded Waiting

---

# Question 6

Binary Semaphore vs Counting Semaphore

| Binary | Counting |
|---------|----------|
| Values 0 or 1 | Values 0 to N |
| One Resource | Multiple Resources |

---

# Google Follow-up Questions

Interviewer:

What is Race Condition?

↓

How can you prevent it?

↓

Semaphore or Mutex?

↓

Why?

↓

How does Java solve this?

↓

What happens if synchronization is removed?

---

# Google Interview Tip

Always explain synchronization with a practical example like:

- ATM
- Railway Reservation
- Online Shopping
- Google Docs

Real-world examples create a stronger impression than definitions alone.