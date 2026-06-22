# 10-Common-Mistakes
# ❌ Common Mistakes

## Mistake 1

Thinking Race Condition and Deadlock are the same.

Wrong.

Race Condition produces incorrect results.

Deadlock stops execution.

---

## Mistake 2

Ignoring Critical Sections.

Every shared variable access should be protected.

---

## Mistake 3

Using Counting Semaphore when Binary Semaphore is enough.

Choose the simplest synchronization primitive.

---

## Mistake 4

Thinking synchronized eliminates every concurrency problem.

It prevents race conditions but does not automatically prevent deadlocks.

---

## Mistake 5

Ignoring lock release.

Always release locks in finally blocks.

---

## Interview Advice

Always explain

Problem

↓

Reason

↓

Solution

↓

Example