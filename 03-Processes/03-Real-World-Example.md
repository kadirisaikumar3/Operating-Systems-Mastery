# 03-Real-World-Example
# 🌍 Real-World Examples of Processes

A process is a running instance of a program. Every application you use daily creates one or more processes.

---

# Example 1: Google Chrome

When you open Google Chrome, multiple processes are created.

Example:

```
Chrome Browser

├── Browser Process

├── Renderer Process (Tab 1)

├── Renderer Process (Tab 2)

├── GPU Process

└── Network Process
```

### Why?

If one tab crashes, the remaining tabs continue working.

---

# Example 2: Microsoft Word

When you open Microsoft Word:

- A new process is created.
- Memory is allocated.
- CPU schedules execution.
- Files are loaded from storage.

Closing Word terminates the process.

---

# Example 3: Android Phone

Opening:

- WhatsApp
- YouTube
- Instagram

creates three different processes.

Android manages them independently.

Background applications may be paused or terminated to save battery.

---

# Example 4: Windows Task Manager

Open Task Manager.

You'll notice hundreds of processes such as:

- explorer.exe
- chrome.exe
- spotify.exe
- notepad.exe

Each has its own:

- PID
- Memory Usage
- CPU Usage

---

# Example 5: Linux

Command:

```
ps -ef
```

Displays all running processes.

Example:

```
PID USER COMMAND

1001 root systemd

2345 user chrome

2450 user code

2501 user firefox
```

---

# Example 6: VS Code

Opening VS Code creates:

- Main Process
- Extension Host Process
- Terminal Process
- Language Server Process

Each performs a separate task.

---

# Interview Insight

Question:

Why does Chrome create multiple processes instead of one?

Answer:

- Better stability
- Better security
- Crash isolation
- Improved performance

---

# Key Takeaways

- Every running application is a process.
- Modern applications often create multiple processes.
- Each process has its own resources.