# 💻 Java Implementation

## FCFS Disk Scheduling

```java
public class FCFS {

    public static void main(String[] args) {

        int[] requests = {98,183,37,122,14,124,65,67};

        int head = 53;

        int seek = 0;

        for(int request : requests){

            seek += Math.abs(head - request);

            head = request;

        }

        System.out.println("Total Seek Time = " + seek);

    }

}
```

---

## SSTF Concept

Steps:

1. Find nearest request.
2. Service it.
3. Update head position.
4. Repeat.

---

## Google Interview Questions

- What is Disk Scheduling?
- FCFS vs SSTF?
- SCAN vs LOOK?
- HDD vs SSD?
- What is RAID?

---

## Google Interview Tip

Always compare:

FCFS

↓

SSTF

↓

SCAN

↓

C-SCAN

↓

LOOK

↓

C-LOOK

Interviewers frequently ask algorithm comparisons.