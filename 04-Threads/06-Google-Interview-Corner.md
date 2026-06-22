# 06-Google-Interview-Corner
# 🚀 Google Interview Corner

This section focuses on thread-related conceptual questions frequently asked in Google, Amazon, Microsoft, Apple, Meta, and other product-based companies.

---

# Question 1

What is a Thread?

Expected Answer

A Thread is the smallest unit of execution within a process.

---

# Question 2

Process vs Thread

| Process | Thread |
|----------|---------|
| Heavyweight | Lightweight |
| Own Memory | Shared Memory |
| Slower | Faster |

---

# Question 3

Why are Threads faster?

Expected Points

- Shared Address Space
- Less Memory
- Faster Creation
- Faster Context Switching

---

# Question 4

Why use Multithreading?

Expected Answer

- Better Responsiveness
- Better Performance
- Efficient CPU Utilization
- Parallel Task Execution

---

# Question 5

Explain Thread Life Cycle.

Expected Flow

New

↓

Runnable

↓

Running

↓

Waiting

↓

Runnable

↓

Running

↓

Terminated

---

# Question 6

Explain User Thread vs Kernel Thread.

Expected Comparison

| User Thread | Kernel Thread |
|-------------|---------------|
| Managed by User Library | Managed by OS |
| Faster | More Secure |
| Lower Overhead | Better Scheduling |

---

# Google Interview Tip

Interviewers often ask:

> "Why is Chrome multi-threaded instead of single-threaded?"

A strong answer should mention:

- Performance
- User Experience
- Background Tasks
- Responsiveness
- Shared Resources