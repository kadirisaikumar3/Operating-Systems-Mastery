# 02-Key-Concepts
# 🔑 Key Concepts

## FCFS (First Come First Serve)

Requests are serviced in arrival order.

Advantages

- Simple
- Fair

Disadvantages

- Large Seek Time

---

## SSTF (Shortest Seek Time First)

Services the nearest request first.

Advantages

- Lower Seek Time

Disadvantages

- Starvation Possible

---

## SCAN (Elevator Algorithm)

Disk head moves in one direction servicing requests.

Then reverses direction.

Advantages

- Better Performance

---

## C-SCAN

Head moves in one direction only.

After reaching the end, returns to the beginning.

Provides more uniform waiting time.

---

## LOOK

Similar to SCAN.

Head only travels as far as the last request.

More efficient than SCAN.

---

## C-LOOK

Similar to C-SCAN.

Returns directly to the first pending request.

Reduces unnecessary movement.

---

## RAID

Redundant Array of Independent Disks.

Used for:

- Performance
- Reliability
- Fault Tolerance

---

## HDD vs SSD

| HDD | SSD |
|------|------|
| Mechanical | Electronic |
| Slower | Faster |
| Cheaper | Expensive |
| Moving Parts | No Moving Parts |

---

## Frequently Asked

- FCFS
- SSTF
- SCAN
- C-SCAN
- LOOK
- RAID