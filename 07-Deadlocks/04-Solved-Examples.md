# 04-Solved-Examples
# ✅ Solved Examples

---

# Example 1

Process P1

↓

Locks Resource R1

↓

Requests R2

Process P2

↓

Locks Resource R2

↓

Requests R1

Result

Deadlock

---

# Example 2

## Coffman Conditions

Suppose

Printer

↓

Scanner

↓

Disk

↓

Network

Processes satisfy

✔ Mutual Exclusion

✔ Hold and Wait

✔ No Preemption

✔ Circular Wait

Result

Deadlock exists.

---

# Example 3

## Resource Allocation Graph

```

P1 → R1

↑      ↓

R2 ← P2

```

A cycle exists.

Deadlock is possible.

---

# Example 4

## Safe State

Available Resources

3

Need

P1 = 1

P2 = 1

P3 = 1

Every process completes.

Safe State.

---

# Example 5

## Unsafe State

Available Resources

0

Every process waits.

Unsafe State.

---

# Example 6

## Prevention

Break one Coffman Condition.

Example

Allow resource preemption.

Deadlock cannot occur.

---

# Google Tip

Always check:

Cycle

↓

Safe State

↓

Banker's Algorithm

before concluding Deadlock.