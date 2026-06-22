# 02-Key-Concepts
# 🔑 Key Concepts

## Demand Paging

Pages are loaded into RAM only when required.

Advantages

- Saves RAM
- Faster startup
- Better memory utilization

---

## Page Fault

Occurs when the requested page is not present in RAM.

Steps

1. CPU requests page
2. Page not found
3. OS loads page from disk
4. Page Table updated
5. Execution resumes

---

## Page Replacement Algorithms

- FIFO
- LRU
- Optimal
- Clock

---

## Thrashing

Occurs when excessive page faults happen.

Symptoms

- High disk activity
- Low CPU utilization
- Poor performance

---

## Working Set Model

Maintains frequently used pages in memory.

Reduces Thrashing.

---

## Copy-on-Write

Memory pages are shared until modification occurs.

Used in:

- Linux
- UNIX
- fork()

---

## Interview Tips

Frequently Asked

- Demand Paging
- Page Fault
- FIFO vs LRU
- Thrashing
- Working Set
- Copy-on-Write

---

## Summary

Virtual Memory improves RAM utilization while enabling larger applications to execute.