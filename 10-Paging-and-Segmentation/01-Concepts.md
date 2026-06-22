# 01-Concepts
# 📚 Paging & Segmentation Concepts

## What is Paging?

Paging is a memory management technique in which logical memory is divided into fixed-size pages and physical memory is divided into fixed-size frames.

Each page can be loaded into any available frame.

---

## Why Paging?

Without Paging

- External Fragmentation occurs.
- Memory allocation becomes difficult.

Paging solves this problem.

---

## Definition

Paging is the process of dividing memory into equal-sized pages and frames.

---

## What is a Page?

A fixed-size block of logical memory.

Example

```

Program

↓

Page 0

Page 1

Page 2

Page 3

```

---

## What is a Frame?

A fixed-size block of physical memory.

RAM

↓

Frame 0

Frame 1

Frame 2

Frame 3

---

## Address Translation

CPU

↓

Logical Address

↓

Page Table

↓

Frame Number

↓

Physical Address

---

## Advantages

- Eliminates External Fragmentation
- Faster Allocation
- Better Memory Utilization

---

## Disadvantages

- Internal Fragmentation
- Page Table Overhead

---

## Interview Tip

Always draw

Page

↓

Frame

↓

Page Table