# 04-Solved-Examples
# ✅ Solved Examples

This section contains interview-oriented examples to strengthen your understanding of Operating System concepts.

---

# Example 1: Identifying the Operating System's Role

### Scenario

A user opens:

- Google Chrome
- Visual Studio Code
- Spotify

all at the same time.

### Question

How does the Operating System handle this situation?

### Solution

The Operating System:

- Creates a separate process for each application.
- Allocates memory to each process.
- Schedules CPU time.
- Manages input/output devices.
- Ensures one application does not interfere with another.

---

# Example 2: Program vs Process

### Scenario

A file named `chrome.exe` is stored on disk.

### Question

Is it a Program or a Process?

### Solution

It is a **Program** because it is stored on disk.

Once the user launches it, it becomes a **Process**.

---

# Example 3: Kernel vs Shell

### Question

A user types:

```
mkdir Projects
```

What happens?

### Solution

1. The Shell accepts the command.
2. The Shell sends a system call to the Kernel.
3. The Kernel creates the directory.
4. The Shell displays the result.

---

# Example 4: Resource Management

### Scenario

Your computer has:

- 8 GB RAM
- 4 CPU cores

Three applications are running:

- Chrome
- VS Code
- Spotify

### Solution

The Operating System:

- Divides CPU time among applications.
- Allocates memory.
- Handles file access.
- Manages network communication.
- Prevents conflicts.

---

# Example 5: Multitasking

### Scenario

You are:

- Watching YouTube
- Downloading a file
- Editing code

### Solution

The CPU rapidly switches between processes.

This creates the illusion that all applications are running simultaneously.

---

# Example 6: Operating System Failure

### Question

What happens if the Operating System crashes?

### Solution

- Running applications stop.
- Hardware becomes inaccessible.
- Unsaved data may be lost.
- The system usually requires a reboot.

---

# Practice Exercise

### Question

Which Operating System component is responsible for interacting directly with hardware?

A. Shell

B. Browser

C. Kernel

D. Compiler

### Answer

✅ **C. Kernel**

---

# Interview Challenge

Explain the journey of opening Google Chrome from the moment the user double-clicks its icon until the browser window appears.

**Expected Points:**

- User action
- Shell receives request
- System call
- Kernel creates process
- Memory allocation
- CPU scheduling
- Browser execution

---

# Summary

These examples demonstrate how Operating Systems work behind the scenes in everyday computing tasks. Understanding these scenarios will help you answer conceptual interview questions confidently.