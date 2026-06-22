# 04-Solved-Examples
# ✅ Solved Examples

---

# Example 1

## Scenario

A user opens Google Chrome and starts downloading a file while watching YouTube.

### Solution

Different threads handle:

- Video Playback
- Network Download
- User Interface

The user experiences smooth playback while the download continues.

---

# Example 2

## Scenario

A document is being typed in Microsoft Word.

Auto Save happens every few seconds.

Question:

Why doesn't typing stop?

### Solution

Because Auto Save executes in a separate thread.

---

# Example 3

## Scenario

An Android application freezes while downloading data.

Question:

Why?

### Solution

The developer performed network operations on the Main(UI) Thread.

Correct approach:

Use a Background Thread.

---

# Example 4

## Scenario

One thread crashes.

Question:

Will the entire process terminate?

### Solution

Not always.

It depends on:

- Exception handling
- Operating System
- Programming language

Poor thread management may terminate the process.

---

# Example 5

## Process vs Thread

Process

↓

Chrome

↓

Thread 1 → UI

Thread 2 → Network

Thread 3 → Rendering

Thread 4 → JavaScript

---

# Practice

Explain why multithreading improves the performance of Visual Studio Code.

---

# Interview Tip

Always explain with practical applications instead of only definitions.