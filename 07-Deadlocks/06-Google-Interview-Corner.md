# 06-Google-Interview-Corner
# 🚀 Google Interview Corner

Deadlocks are one of the highest-priority Operating System interview topics.

---

# Question 1

What is Deadlock?

Expected Answer

Deadlock is a permanent blocking condition where each process waits for a resource held by another waiting process.

---

# Question 2

Explain Coffman Conditions.

Expected Answer

- Mutual Exclusion
- Hold and Wait
- No Preemption
- Circular Wait

All four must exist simultaneously.

---

# Question 3

How can Deadlocks be prevented?

Expected Answer

Break any one Coffman Condition.

---

# Question 4

Deadlock Prevention vs Avoidance

| Prevention | Avoidance |
|------------|-----------|
| Break Conditions | Check Safe State |
| Simpler | Uses Banker's Algorithm |
| Less Flexible | More Efficient |

---

# Question 5

What is Banker's Algorithm?

Expected Answer

A Deadlock Avoidance algorithm that grants resources only if the system remains in a Safe State.

---

# Question 6

Deadlock vs Starvation

| Deadlock | Starvation |
|----------|------------|
| Processes wait forever | One process waits indefinitely |
| Circular Waiting | Resource Allocation Issue |

---

# Google Follow-up Questions

Interviewer

Explain Deadlock.

↓

How does Banker's Algorithm work?

↓

What is Safe State?

↓

Unsafe State?

↓

Can Java programs deadlock?

↓

How do you prevent it?

---

# Google Interview Tip

Always draw

Resource Allocation Graph

↓

Explain Coffman Conditions

↓

Safe State

↓

Solution

This is the expected interview flow.