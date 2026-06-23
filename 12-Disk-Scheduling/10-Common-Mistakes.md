# 10-Common-Mistakes
# ❌ Common Mistakes

## Mistake 1

Ignoring Seek Time.

Seek Time has the largest impact on disk performance.

---

## Mistake 2

Thinking SSTF is always best.

SSTF may cause starvation.

---

## Mistake 3

Confusing SCAN and LOOK.

SCAN goes to disk end.

LOOK stops at last request.

---

## Mistake 4

Ignoring Rotational Latency.

Disk performance depends on both seek time and rotation.

---

## Mistake 5

Thinking SSD uses disk head movement.

Wrong.

SSD has no moving parts.

---

## Interview Advice

Disk

↓

Seek Time

↓

Scheduling Algorithm

↓

Performance