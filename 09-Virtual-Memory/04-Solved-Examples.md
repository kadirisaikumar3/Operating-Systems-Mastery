# 04-Solved-Examples
# ✅ Solved Examples

---

# Example 1

## FIFO Page Replacement

Reference String

```
7 0 1 2 0 3 0 4
```

Frames

```
3
```

Page Faults

```
7
```

FIFO removes the oldest page first.

---

# Example 2

## LRU Page Replacement

Reference String

```
7 0 1 2 0 3 0 4
```

Frames

```
3
```

Least Recently Used page is replaced.

LRU generally produces fewer page faults than FIFO.

---

# Example 3

## Optimal Algorithm

Replace the page that will not be used for the longest future time.

Produces the minimum possible page faults.

Used as a benchmark.

---

# Example 4

## Clock Algorithm

Uses a circular queue with reference bits.

Provides performance close to LRU with lower overhead.

---

# Example 5

## Page Fault

CPU requests Page 8.

Page 8 not present in RAM.

↓

OS loads Page 8 from disk.

↓

Execution resumes.

---

# Example 6

## Thrashing

Available RAM

2 GB

Applications require

8 GB

Continuous Page Faults occur.

CPU utilization drops significantly.

---

# Google Interview Tip

Always compare

FIFO

↓

LRU

↓

Optimal

↓

Clock