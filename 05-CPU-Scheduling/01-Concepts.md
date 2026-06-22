# 01-Concepts
# 🖥️ CPU Scheduling Concepts

## What is CPU Scheduling?

CPU Scheduling is the process of selecting one process from the Ready Queue and allocating the CPU to it.

The Operating System uses scheduling algorithms to decide which process should execute next.

---

## Why is CPU Scheduling Needed?

In a multiprogramming environment, many processes wait for CPU execution.

Without scheduling:

- CPU remains idle.
- Applications become slow.
- System performance decreases.

CPU Scheduling ensures efficient CPU utilization.

---

## CPU Scheduling Flow

```

Ready Queue

↓

CPU Scheduler

↓

CPU

↓

Running Process

```

---

## Objectives of CPU Scheduling

- Maximize CPU Utilization
- Increase Throughput
- Reduce Waiting Time
- Reduce Turnaround Time
- Reduce Response Time
- Improve Fairness

---

## Types of Scheduling

### Non-Preemptive

Once a process starts executing, it continues until completion or blocking.

Examples

- FCFS
- SJF

---

### Preemptive

A running process can be interrupted.

Examples

- SRTF
- Round Robin
- Priority (Preemptive)

---

## Scheduling Components

- Ready Queue
- CPU Scheduler
- Dispatcher
- Running Process
- Waiting Queue

---

## Real-World Example

Imagine a bank with one cashier.

Customers arrive one after another.

The cashier decides which customer to serve first.

This is similar to CPU Scheduling.

---

## Google Interview Tip

Always explain:

Ready Queue

↓

Scheduler

↓

CPU

↓

Execution

instead of simply defining CPU Scheduling.

---

## Key Takeaways

- CPU Scheduling selects the next process.
- Scheduling improves CPU efficiency.
- Different algorithms have different advantages.