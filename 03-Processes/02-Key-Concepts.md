# 02-Key-Concepts
# 🔑 Key Concepts

Understanding these concepts is essential before learning CPU Scheduling and Process Synchronization.

---

# Process States

A process moves through different states during execution.

Main states:

- New
- Ready
- Running
- Waiting (Blocked)
- Terminated

---

# Process State Diagram

```

New

↓

Ready

↓

Running

↓

Waiting

↓

Ready

↓

Running

↓

Terminated

```

---

# Process Control Block (PCB)

PCB is a data structure maintained by the Operating System for every process.

It stores:

- Process ID
- Process State
- CPU Registers
- Program Counter
- Memory Information
- Scheduling Information
- Open Files

---

# Context Switching

Context Switching is the process of saving the state of one process and loading another process.

Purpose:

- Multitasking
- Efficient CPU utilization

---

# Process Creation

A new process is created when:

- User starts an application.
- Parent process creates child process.
- Operating System starts a service.

---

# Process Termination

A process terminates when:

- Execution completes.
- User closes application.
- Fatal error occurs.
- Operating System terminates it.

---

# Process Identifier (PID)

Every process has a unique identifier called PID.

Example:

Chrome.exe

↓

PID = 5432

---

# Parent and Child Processes

A process can create another process.

Parent

↓

Child

Example:

Chrome

↓

Chrome Renderer Process

---

# Interview Tips

Frequently Asked

- What is PCB?
- Explain Context Switching.
- Explain Process States.
- Explain Process Creation.
- Program vs Process?

---

# Summary

These concepts form the foundation for CPU Scheduling, Threads, Deadlocks and Synchronization.