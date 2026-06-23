# 09-Cheat-Sheet
# 📋 Disk Scheduling Cheat Sheet

## Disk Access Time

Seek Time

+

Rotational Latency

+

Transfer Time

---

## Algorithms

| Algorithm | Advantage | Disadvantage |
|------------|------------|-------------|
| FCFS | Simple | High Seek Time |
| SSTF | Fast | Starvation |
| SCAN | Better Throughput | More Movement |
| C-SCAN | Uniform Wait Time | Extra Jump |
| LOOK | Efficient | Slight Complexity |
| C-LOOK | Best Optimization | Complex |

---

## Google Tip

Always compare:

FCFS

↓

SSTF

↓

SCAN

↓

LOOK