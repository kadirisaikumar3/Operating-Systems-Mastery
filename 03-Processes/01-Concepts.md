# 01-Concepts
# 📘 Process Concepts

## What is a Process?

A **Process** is a program that is currently executing.

When a program is stored on disk, it is simply a file. Once it is loaded into memory and begins execution, it becomes a **Process**.

---

# Definition

> **Process:** A program in execution that has its own memory, CPU registers, program counter, stack, and resources.

---

# Why are Processes Needed?

Processes allow multiple applications to run simultaneously while sharing system resources efficiently.

Examples:

- Google Chrome
- VS Code
- Spotify
- Microsoft Word

Each of these runs as a separate process.

---

# Program vs Process

| Program | Process |
|----------|----------|
| Passive | Active |
| Stored on Disk | Running in Memory |
| Static | Dynamic |

---

# Components of a Process

Every process contains:

- Program Code (Text Section)
- Data Section
- Heap
- Stack
- Program Counter
- CPU Registers

---

# Process Memory Layout

```

+----------------------+
| Stack |
+----------------------+
| Heap |
+----------------------+
| Data |
+----------------------+
| Code |
+----------------------+

```

---

# Characteristics of a Process

- Dynamic
- Independent
- Has Process ID (PID)
- Own Memory Space
- Own Execution Context

---

# Advantages

- Better multitasking
- Resource sharing
- Isolation between applications
- Improved reliability

---

# Real-World Example

Opening Google Chrome creates a new process.

Opening another Chrome window creates another process.

Opening another Chrome tab may create another process depending on Chrome's architecture.

---

# Google Interview Tip

Always explain:

Program

↓

Loaded into Memory

↓

CPU Executes

↓

Becomes Process

---

# Key Takeaways

- Process = Program in Execution
- Every running application is a Process.
- Processes have their own memory and resources.