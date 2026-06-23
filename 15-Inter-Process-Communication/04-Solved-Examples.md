# 04-Solved-Examples
# ✅ Solved Examples

---

# Example 1

## Shared Memory

Process A

Writes Data

↓

Shared Memory

↓

Process B

Reads Data

Advantage

Very Fast Communication

---

# Example 2

## Message Passing

Process A

↓

Send Message

↓

Kernel Queue

↓

Receive Message

↓

Process B

Advantage

Safe Communication

---

# Example 3

## Pipe

Parent Process

↓

Pipe

↓

Child Process

Characteristics

- Half Duplex
- Local Communication

---

# Example 4

## Named Pipe

Process A

↓

FIFO File

↓

Process B

Works between unrelated processes.

---

# Example 5

## Socket

Client

↓

Socket

↓

Server

↓

Response

Used in network communication.

---

# Example 6

## Semaphore

Semaphore = 1

Process A enters Critical Section

↓

Semaphore = 0

↓

Process B waits

↓

Process A exits

↓

Semaphore = 1

---

# Google Tip

Always compare

Shared Memory

↓

Message Passing

↓

Sockets