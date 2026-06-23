# 10-Common-Mistakes
# ❌ Common Mistakes

## Mistake 1

Thinking applications access hardware directly.

Wrong.

They use System Calls.

---

## Mistake 2

Confusing User Mode and Kernel Mode.

User Mode

Restricted

Kernel Mode

Privileged

---

## Mistake 3

Thinking fork() runs a new program.

fork() only creates a process.

exec() loads a new program.

---

## Mistake 4

Ignoring System Call Cost.

Mode switching introduces overhead.

---

## Mistake 5

Confusing Function Calls with System Calls.

Function Call

User Space

System Call

Kernel Space

---

## Interview Advice

User

↓

System Call

↓

Kernel

↓

Hardware