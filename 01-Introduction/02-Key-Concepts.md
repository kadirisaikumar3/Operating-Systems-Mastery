# 02-Key-Concepts
# 🔑 Key Concepts of Operating Systems

Understanding these core concepts is essential before learning advanced Operating System topics.

---

# 1. Kernel

The **Kernel** is the core component of an Operating System.

It directly communicates with hardware and manages:

- CPU
- Memory
- Devices
- Processes

Without the kernel, an Operating System cannot function.

---

# 2. Shell

The **Shell** acts as an interface between the user and the Operating System.

Types:

- Command Line Interface (CLI)
- Graphical User Interface (GUI)

Examples:

- Windows Command Prompt
- PowerShell
- Linux Bash
- macOS Terminal

---

# 3. Process

A **Process** is a program that is currently executing.

Example:

When you open Google Chrome, it becomes a running process.

---

# 4. Program

A **Program** is a set of instructions stored on disk.

It becomes a **Process** only when executed.

---

# 5. Thread

A **Thread** is the smallest unit of execution inside a process.

Example:

A web browser can download files while simultaneously playing a video.

---

# 6. CPU Scheduling

CPU Scheduling decides:

> Which process should execute next?

Scheduling improves CPU utilization and system performance.

---

# 7. Memory Management

The Operating System:

- Allocates memory
- Deallocates memory
- Protects memory
- Optimizes memory usage

---

# 8. File System

A File System organizes data into files and directories.

Common file systems:

- NTFS
- FAT32
- ext4
- APFS

---

# 9. Device Drivers

Device Drivers allow the Operating System to communicate with hardware devices.

Examples:

- Printer Driver
- Graphics Driver
- Audio Driver
- Network Driver

---

# 10. System Calls

Applications request Operating System services through **System Calls**.

Examples:

- Open File
- Read File
- Write File
- Create Process
- Allocate Memory

---

# Operating System Components

```
Operating System
│
├── Kernel
├── Shell
├── File System
├── Device Drivers
├── Memory Manager
├── Scheduler
└── System Calls
```

---

# Important Differences

| Program | Process |
|----------|----------|
| Stored on disk | Running in memory |
| Passive | Active |
| Static | Dynamic |

---

| Kernel | Shell |
|---------|-------|
| Core of OS | User Interface |
| Manages hardware | Accepts user commands |

---

# Interview Tips

Frequently Asked Questions:

- What is Kernel?
- Difference between Program and Process?
- Difference between Process and Thread?
- What is Shell?
- What are System Calls?

These are among the most commonly asked Operating System interview questions.

---

# Summary

Mastering these concepts will make learning advanced topics like Processes, Threads, CPU Scheduling, Deadlocks, and Memory Management much easier.