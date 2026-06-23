# 01-Concepts
# 💽 Disk Scheduling Concepts

## What is Disk Scheduling?

Disk Scheduling is the process of deciding the order in which disk I/O requests are serviced.

The goal is to minimize disk access time and improve system performance.

---

## Why is Disk Scheduling Needed?

Without Disk Scheduling:

- Disk head movement increases.
- Seek time increases.
- Performance decreases.

Disk Scheduling optimizes disk operations.

---

## Disk Structure

A disk consists of:

- Platters
- Tracks
- Sectors
- Read/Write Head

---

## Disk Access Time

Disk Access Time =

Seek Time

+

Rotational Latency

+

Transfer Time

---

## Seek Time

Time required to move disk head to the required track.

Most important factor in performance.

---

## Rotational Latency

Time waiting for the required sector to rotate under the disk head.

---

## Transfer Time

Time required to transfer data between disk and memory.

---

## Goal of Disk Scheduling

- Minimize Seek Time
- Improve Throughput
- Reduce Waiting Time
- Improve Response Time

---

## Real World Example

Suppose requests arrive for:

98, 183, 37, 122, 14, 124, 65, 67

A good scheduling algorithm reduces unnecessary head movement.

---

## Interview Tip

Always remember:

Disk Access Time

=

Seek Time

+

Rotational Latency

+

Transfer Time