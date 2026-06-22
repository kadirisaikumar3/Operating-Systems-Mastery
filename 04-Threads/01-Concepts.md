# 01-Concepts
# 🧵 Thread Concepts

## What is a Thread?

A **Thread** is the smallest unit of execution inside a process.

A process may contain one or more threads that execute concurrently while sharing the same memory and resources.

> **Definition:**  
> A Thread is the smallest schedulable unit of execution within a process.

---

# Why are Threads Needed?

Threads improve:

- Responsiveness
- Performance
- Resource Sharing
- Parallelism
- CPU Utilization

Instead of creating multiple processes (which is expensive), applications create multiple threads.

---

# Process vs Thread

| Process | Thread |
|----------|---------|
| Heavyweight | Lightweight |
| Own Memory | Shared Memory |
| Higher Creation Cost | Lower Creation Cost |
| Slower Context Switch | Faster Context Switch |

---

# Thread Components

Every thread has its own:

- Thread ID (TID)
- Program Counter
- Registers
- Stack

Threads share:

- Code Segment
- Heap
- Data Segment
- Open Files

---

# Thread Memory Layout

```

Process

+----------------------------+

| Shared Code |

| Shared Heap |

| Shared Data |

+----------------------------+

Thread 1 → Stack

Thread 2 → Stack

Thread 3 → Stack

```

---

# Advantages of Threads

- Faster execution
- Better CPU utilization
- Improved responsiveness
- Easy communication
- Lower memory consumption

---

# Disadvantages

- Synchronization issues
- Race conditions
- Deadlocks
- Debugging complexity

---

# Real-World Example

Google Chrome

One browser process creates multiple threads for:

- Rendering
- Networking
- JavaScript Engine
- User Interface

---

# Google Interview Tip

Always remember:

A Process owns resources.

A Thread executes tasks.

---

# Key Takeaways

- Thread = Smallest execution unit.
- Multiple threads can exist inside one process.
- Threads share resources but have separate execution stacks.