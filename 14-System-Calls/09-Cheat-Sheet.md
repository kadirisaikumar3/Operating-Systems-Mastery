# 09-Cheat-Sheet
# 📋 System Calls Cheat Sheet

## Execution Flow

User Mode

↓

System Call

↓

Kernel Mode

↓

Service Execution

↓

Return to User Mode

---

## Categories

| Category | Examples |
|-----------|-----------|
| Process | fork(), exec() |
| File | open(), read() |
| Device | ioctl() |
| Information | getpid() |
| Communication | socket(), pipe() |
| Protection | chmod() |

---

## Google Tip

Remember

fork()

↓

exec()

↓

wait()

↓

exit()