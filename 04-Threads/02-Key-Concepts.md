# 02-Key-Concepts
# 🔑 Key Concepts

Understanding these concepts is essential before learning CPU Scheduling and Synchronization.

---

# Thread Life Cycle

A thread moves through different states during execution.

States:

- New
- Runnable
- Running
- Waiting
- Blocked
- Terminated

---

# Thread State Diagram

```

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

```

---

# Thread Control Block (TCB)

The Operating System maintains a **Thread Control Block (TCB)** for every thread.

It stores:

- Thread ID
- Thread State
- CPU Registers
- Program Counter
- Stack Pointer
- Scheduling Information

---

# User-Level Threads

Managed by:

User Thread Library

Advantages:

- Fast
- Lightweight

Disadvantages:

- Kernel is unaware of them.

Examples:

- Java Green Threads
- POSIX User Threads

---

# Kernel-Level Threads

Managed directly by the Operating System.

Advantages:

- Better scheduling
- Better parallelism

Disadvantages:

- Higher overhead

Examples:

- Windows Threads
- Linux pthreads

---

# Multithreading Models

### Many-to-One

Many user threads map to one kernel thread.

---

### One-to-One

One user thread maps to one kernel thread.

Windows uses this model.

---

### Many-to-Many

Many user threads map to many kernel threads.

Provides flexibility and scalability.

---

# Thread Scheduling

The Operating System schedules runnable threads to execute on the CPU.

Scheduling depends on:

- Priority
- Time Slice
- CPU Availability

---

# Interview Tips

Frequently Asked:

- Process vs Thread
- User Thread vs Kernel Thread
- What is TCB?
- Explain Thread Life Cycle.
- Why are Threads faster than Processes?

---

# Summary

Threads provide efficient concurrency within a process by sharing resources while maintaining separate execution contexts.