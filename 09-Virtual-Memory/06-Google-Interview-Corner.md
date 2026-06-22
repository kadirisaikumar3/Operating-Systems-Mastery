# 06-Google-Interview-Corner
# 🚀 Google Interview Corner

Virtual Memory is one of Google's favorite Operating System topics.

---

# Question 1

What is Virtual Memory?

Expected Answer

Virtual Memory allows execution of programs larger than RAM by using disk as an extension of memory.

---

# Question 2

Demand Paging vs Swapping

| Demand Paging | Swapping |
|--------------|----------|
| Loads required pages | Moves entire process |
| Faster | Slower |
| Better Memory Usage | Higher Overhead |

---

# Question 3

FIFO vs LRU

| FIFO | LRU |
|------|-----|
| Oldest Page | Least Recently Used Page |
| Simple | Better Performance |
| Belady's Anomaly | No Belady's Anomaly |

---

# Question 4

What is Thrashing?

Expected Answer

Thrashing occurs when excessive page faults cause the system to spend more time swapping pages than executing instructions.

---

# Question 5

What is Copy-on-Write?

Expected Answer

Memory pages are shared until one process modifies them.

---

# Question 6

Which algorithm is best?

Expected Answer

Optimal Algorithm gives the minimum page faults but cannot be implemented in practice because it requires future knowledge.

---

# Google Follow-up Questions

Interviewer

What is Virtual Memory?

↓

Demand Paging?

↓

Page Fault?

↓

FIFO?

↓

LRU?

↓

Thrashing?

↓

Belady's Anomaly?

↓

Working Set?

---

# Google Interview Tip

Always draw

CPU

↓

Virtual Address

↓

Page Table

↓

RAM

↓

Disk

This diagram clearly explains Virtual Memory during interviews.