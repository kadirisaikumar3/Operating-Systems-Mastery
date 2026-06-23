# 04-Solved-Examples
# ✅ Solved Examples

---

# Example 1

## File Open

Program

↓

open("data.txt")

↓

Kernel checks file.

↓

File Descriptor = 3

Returned to process.

---

# Example 2

## File Read

read(fd, buffer, size)

↓

Kernel reads data.

↓

Copies data to buffer.

↓

Returns bytes read.

---

# Example 3

## Process Creation

fork()

↓

Parent Process

↓

Child Process

Both continue execution.

---

# Example 4

## Program Execution

exec()

↓

Current process image replaced.

↓

New program starts.

---

# Example 5

## Process Termination

exit()

↓

Kernel releases resources.

↓

Process removed.

---

# Example 6

## Socket Communication

socket()

↓

connect()

↓

send()

↓

recv()

↓

close()

---

# Google Tip

Know the sequence:

fork()

↓

exec()

↓

wait()

↓

exit()