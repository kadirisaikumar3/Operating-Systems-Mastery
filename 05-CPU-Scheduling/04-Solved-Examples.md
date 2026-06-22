# 04-Solved-Examples
# ✅ Solved Examples

---

# Example 1 – FCFS Scheduling

Processes:

| Process | Arrival Time | Burst Time |
|----------|--------------|-----------:|
| P1 | 0 | 4 |
| P2 | 1 | 3 |
| P3 | 2 | 2 |

### Gantt Chart

```

0      4      7      9

| P1 | P2 | P3 |

```

### Waiting Time

P1 = 0

P2 = 4 - 1 = 3

P3 = 7 - 2 = 5

Average Waiting Time

= (0 + 3 + 5) / 3

= 2.67

---

# Example 2 – SJF Scheduling

Processes

| Process | Burst |
|----------|------:|
| P1 | 6 |
| P2 | 2 |
| P3 | 4 |

Execution Order

P2 → P3 → P1

Advantages

- Lower average waiting time
- Better throughput

---

# Example 3 – Round Robin

Time Quantum = 2

Processes

P1 = 5

P2 = 4

P3 = 2

Gantt Chart

```

P1 P2 P3 P1 P2 P1

```

Each process receives equal CPU time.

---

# Example 4 – Priority Scheduling

| Process | Priority |
|----------|---------:|
| P1 | 3 |
| P2 | 1 |
| P3 | 2 |

Execution

P2 → P3 → P1

(Lower number = Higher priority)

---

# Example 5

Question

Which algorithm minimizes average waiting time?

Answer

Shortest Job First (SJF)

---

# Interview Tip

Always draw the Gantt Chart before calculating Waiting Time, Turnaround Time, or Response Time.