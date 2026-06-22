# 04-Solved-Examples
# ✅ Solved Examples

---

# Example 1

## Scenario

A user opens Google Chrome.

### What happens?

Solution

1. Chrome executable is loaded.
2. Operating System creates a new process.
3. PID is assigned.
4. Memory is allocated.
5. CPU begins execution.

---

# Example 2

## Scenario

A user opens three Chrome tabs.

Question

How many processes are created?

Solution

Modern Chrome creates multiple processes:

- Browser Process
- Renderer Process (Tab 1)
- Renderer Process (Tab 2)
- Renderer Process (Tab 3)

Additional GPU and Network processes may also exist.

---

# Example 3

## Scenario

A process crashes.

Question

Will every application crash?

Solution

No.

Each process has its own memory space.

Only the crashed process terminates.

---

# Example 4

## Scenario

A process enters Waiting State.

Question

Why?

Solution

Because it is waiting for:

- Disk I/O
- Keyboard Input
- Mouse Input
- Network Response

---

# Example 5

## Scenario

CPU starts executing another process.

Question

What happens?

Solution

Context Switching occurs.

Operating System:

- Saves current process state.
- Loads next process state.
- CPU starts executing the new process.

---

# Example 6

## Process Life Cycle

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

# Practice

Explain:

How does WhatsApp become a Process after tapping its icon?

---

# Interview Tip

Always explain process execution step-by-step instead of giving only definitions.