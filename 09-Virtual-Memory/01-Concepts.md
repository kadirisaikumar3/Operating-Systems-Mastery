# 01-Concepts
# 🧠 Virtual Memory Concepts

## What is Virtual Memory?

Virtual Memory is a memory management technique that allows programs larger than the available RAM to execute by using secondary storage (disk) as an extension of main memory.

Instead of loading the entire program into RAM, only the required pages are loaded.

---

## Definition

> Virtual Memory is a technique that creates the illusion of a larger main memory using both RAM and disk storage.

---

## Why is Virtual Memory Needed?

Without Virtual Memory:

- Large programs cannot execute.
- Multiprogramming becomes limited.
- RAM utilization is poor.

With Virtual Memory:

- Larger programs run efficiently.
- Better CPU utilization.
- Higher degree of multiprogramming.

---

## Virtual Memory Flow

CPU

↓

Virtual Address

↓

MMU

↓

Page Table

↓

Physical Memory

↓

Disk (if page missing)

---

## Advantages

- Efficient RAM usage
- Supports large applications
- Better multitasking
- Faster execution
- Reduced memory waste

---

## Disadvantages

- Page Fault overhead
- Disk access is slower than RAM
- Thrashing may occur

---

## Real-World Example

Google Chrome loads only active tabs into memory.

Inactive tabs are moved out, reducing RAM usage.

---

## Interview Tip

Always explain:

Virtual Address

↓

Page Table

↓

Physical Memory

↓

Disk
