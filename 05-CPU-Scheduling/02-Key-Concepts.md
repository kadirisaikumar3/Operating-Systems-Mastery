# 02-Key-Concepts
# 🔑 Key Concepts

Before learning scheduling algorithms, understand these important concepts.

---

# CPU Scheduler

Selects the next process from the Ready Queue.

---

# Dispatcher

Transfers CPU control to the selected process.

Dispatcher responsibilities:

- Context Switching
- Mode Switching
- Jump to User Program

---

# Scheduling Criteria

## CPU Utilization

Percentage of time CPU remains busy.

Higher is better.

---

## Throughput

Number of completed processes per unit time.

Higher is better.

---

## Turnaround Time (TAT)

Time from process submission to completion.

Formula

```

TAT = Completion Time - Arrival Time

```

Lower is better.

---

## Waiting Time (WT)

Time spent waiting in Ready Queue.

Formula

```

WT = Turnaround Time - Burst Time

```

Lower is better.

---

## Response Time (RT)

Time taken for a process to get CPU for the first time.

Formula

```

RT = First CPU Allocation - Arrival Time

```

Lower is better.

---

# Types of Schedulers

### Long-Term Scheduler

Controls which processes enter memory.

---

### Short-Term Scheduler

Chooses the next process for CPU execution.

---

### Medium-Term Scheduler

Temporarily removes processes from memory.

---

# Preemptive vs Non-Preemptive

| Non-Preemptive | Preemptive |
|----------------|------------|
| Cannot Interrupt | Can Interrupt |
| Simple | More Complex |
| Less Overhead | Higher Overhead |

---

# Scheduling Algorithms Covered

- FCFS
- SJF
- SRTF
- Priority
- Round Robin
- Multilevel Queue
- Multilevel Feedback Queue

---

# Interview Tips

Frequently Asked

- Difference between Preemptive and Non-Preemptive?
- What is Dispatcher?
- What is Response Time?
- What is Turnaround Time?
- Difference between Scheduler and Dispatcher?

---

# Summary

Understanding these concepts makes solving scheduling problems much easier.