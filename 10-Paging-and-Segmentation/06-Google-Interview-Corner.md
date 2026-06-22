# 06-Google-Interview-Corner
# 🚀 Google Interview Corner

Paging and Segmentation are among Google's favorite Memory Management topics.

---

# Question 1

What is Paging?

Expected Answer

Paging divides logical memory into fixed-size pages and physical memory into fixed-size frames.

---

# Question 2

Paging vs Segmentation

| Paging | Segmentation |
|---------|--------------|
| Fixed Size | Variable Size |
| Page Table | Segment Table |
| Internal Fragmentation | External Fragmentation |

---

# Question 3

How is Address Translation performed?

Expected Answer

Logical Address

↓

Page Number

↓

Page Table

↓

Frame Number

↓

Physical Address

---

# Question 4

Why is Paging used?

Expected Answer

To eliminate External Fragmentation and improve memory utilization.

---

# Question 5

What is Shared Memory?

Expected Answer

Multiple processes share the same physical memory for efficient communication.

---

# Google Follow-up Questions

Interviewer

What is Paging?

↓

What is a Frame?

↓

How does Address Translation work?

↓

Why do we need Page Tables?

↓

Paging vs Segmentation?

↓

Virtual Memory?

↓

MMU?

---

# Google Interview Tip

Always draw

Logical Address

↓

Page Number

↓

Page Table

↓

Frame

↓

RAM

A diagram helps explain address translation clearly.