# 06-Google-Interview-Corner
# 🚀 Google Interview Corner

These conceptual questions are commonly asked in interviews at Google, Microsoft, Amazon, Meta, Apple, and other product-based companies.

---

# Question 1

What is a Process?

Expected Answer:

A process is a program in execution with its own memory space, CPU registers, program counter, stack, and system resources.

---

# Question 2

Program vs Process

| Program | Process |
|----------|----------|
| Passive | Active |
| Stored on Disk | Running in Memory |
| No Execution | Executing |

---

# Question 3

Explain PCB.

Expected Points

- Process ID
- Process State
- CPU Registers
- Program Counter
- Scheduling Information
- Memory Information

---

# Question 4

Explain Context Switching.

Expected Flow

Running Process

↓

Save Context

↓

Load New Process Context

↓

Resume Execution

---

# Question 5

Why is Context Switching expensive?

Expected Answer

Because the CPU must:

- Save registers
- Save program counter
- Load another process state
- Flush/reload cache (depending on architecture)

This introduces overhead.

---

# Question 6

Why does Chrome create multiple processes?

Expected Points

- Stability
- Security
- Crash isolation
- Better resource management

---

# Google Interview Tip

Interviewers often ask:

> "What happens internally when you double-click Chrome?"

Explain:

Application

↓

Process Creation

↓

PID Assignment

↓

Memory Allocation

↓

CPU Scheduling

↓

Execution

This demonstrates a strong understanding of Operating System internals.