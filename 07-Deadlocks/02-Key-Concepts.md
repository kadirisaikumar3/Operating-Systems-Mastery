# 02-Key-Concepts
# 🔑 Key Concepts

---

# Coffman Conditions

All four conditions must hold simultaneously for a Deadlock to occur.

---

## 1. Mutual Exclusion

At least one resource must be non-shareable.

Example

Printer

---

## 2. Hold and Wait

A process holds one resource while waiting for another.

---

## 3. No Preemption

Resources cannot be forcibly taken away.

Only the owning process can release them.

---

## 4. Circular Wait

A circular chain of processes exists.

Example

```

P1 → R1

↓

P2 ← R2

```

---

# Resource Allocation Graph (RAG)

Used to represent relationships between processes and resources.

Components

- Process
- Resource
- Request Edge
- Allocation Edge

If the graph contains a cycle,

Deadlock may exist.

---

# Safe State

A system is in a Safe State if all processes can complete successfully.

---

# Unsafe State

An Unsafe State may eventually lead to Deadlock.

---

# Deadlock Handling

- Prevention
- Avoidance
- Detection
- Recovery

---

# Banker's Algorithm

Deadlock Avoidance Algorithm.

Checks whether allocating a resource keeps the system in a Safe State.

---

# Frequently Asked

- Coffman Conditions
- Safe State
- Banker's Algorithm
- Resource Allocation Graph

---

# Summary

Understanding these concepts makes Deadlock problems much easier to solve.