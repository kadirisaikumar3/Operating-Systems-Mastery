# 10-Common-Mistakes
# ❌ Common Mistakes

## Mistake 1

Thinking Process and Thread are the same.

Wrong.

A Process contains one or more Threads.

---

## Mistake 2

Thinking Threads have separate memory.

Wrong.

Threads share Process memory.

---

## Mistake 3

Ignoring Synchronization.

Shared memory requires synchronization.

---

## Mistake 4

Thinking Threads are independent.

Wrong.

Threads depend on the parent Process.

---

## Mistake 5

Confusing User Threads with Kernel Threads.

Remember:

User Threads → User Library

Kernel Threads → Operating System

---

## Interview Advice

Always compare

Process

↓

Thread

↓

Shared Resources

↓

Performance
