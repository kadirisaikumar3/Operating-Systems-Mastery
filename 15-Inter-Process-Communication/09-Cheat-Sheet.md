# 09-Cheat-Sheet
# 📋 IPC Cheat Sheet

## Communication Flow

Process A

↓

IPC Mechanism

↓

Process B

---

## IPC Comparison

| IPC | Speed | Network Support |
|------|--------|----------------|
| Shared Memory | Fastest | No |
| Message Passing | Medium | Yes |
| Pipe | Fast | No |
| Named Pipe | Fast | Limited |
| Socket | Medium | Yes |

---

## Synchronization Tools

✔ Semaphore

✔ Mutex

✔ Monitor

---

## Google Tip

Always compare

Shared Memory

↓

Message Passing

↓

Socket