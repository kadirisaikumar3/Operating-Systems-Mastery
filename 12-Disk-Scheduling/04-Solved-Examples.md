# 04-Solved-Examples
# ✅ Solved Examples

---

# Example 1

## FCFS

Requests

98, 183, 37, 122

Head

53

Movement

53 → 98 = 45

98 → 183 = 85

183 → 37 = 146

37 → 122 = 85

Total Seek Time

361

---

# Example 2

## SSTF

Requests

98, 183, 37, 122

Head

53

Nearest Request

37

Then

98

Then

122

Then

183

Total Seek Time is less than FCFS.

---

# Example 3

## SCAN

Head moves in one direction servicing all requests.

Then reverses.

Also called:

Elevator Algorithm.

---

# Example 4

## C-SCAN

Head moves in one direction.

After reaching end:

Returns to beginning.

Provides uniform waiting time.

---

# Example 5

## LOOK

Head only travels up to the last request.

Reduces unnecessary movement.

---

# Example 6

## Disk Access Time

Seek Time

10 ms

Rotational Latency

4 ms

Transfer Time

2 ms

Disk Access Time

16 ms

---

# Google Tip

Always calculate total head movement before comparing algorithms.