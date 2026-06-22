# 04-Solved-Examples
# ✅ Solved Examples

---

# Example 1

## Race Condition

Shared Variable

```
count = 10
```

Thread A

```
count++
```

Thread B

```
count++
```

Without synchronization

Expected

```
12
```

Possible Result

```
11
```

Reason

Both threads update the same variable simultaneously.

---

# Example 2

## Critical Section

```
balance = balance - amount;
```

Only one thread should execute this code at a time.

Use

- Mutex
- Semaphore
- synchronized

---

# Example 3

## Binary Semaphore

Semaphore Value

```
1
```

Process A

↓

Enters Critical Section

↓

Semaphore becomes

```
0
```

Process B waits.

---

# Example 4

## Producer Consumer

Producer

↓

Buffer

↓

Consumer

Semaphore controls access to the shared buffer.

---

# Example 5

## Peterson's Solution

Process P0

↓

Flag = true

↓

Turn = P1

↓

Enter Critical Section

If P1 is also interested,

Only one process proceeds.

---

# Interview Tip

Always explain synchronization problems using diagrams whenever possible.