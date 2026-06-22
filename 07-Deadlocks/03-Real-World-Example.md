# 03-Real-World-Example
# 🌍 Real-World Examples

Deadlocks occur in many real-world systems whenever multiple processes compete for limited resources.

---

# Example 1: ATM Banking System

Suppose:

ATM 1 locks

Customer Database

↓

Needs Transaction Server

ATM 2 locks

Transaction Server

↓

Needs Customer Database

Result

Both ATMs wait forever.

This is a Deadlock.

---

# Example 2: Railway Reservation

Process A

↓

Locks Seat Database

↓

Needs Payment Server

Process B

↓

Locks Payment Server

↓

Needs Seat Database

Neither process can continue.

---

# Example 3: Database Management System

Transaction T1

Locks Table A

↓

Requests Table B

Transaction T2

Locks Table B

↓

Requests Table A

Result

Deadlock occurs.

Database systems periodically detect and resolve deadlocks.

---

# Example 4: Cloud Computing

Two virtual machines request shared storage resources.

VM1

↓

Storage A

↓

Needs Storage B

VM2

↓

Storage B

↓

Needs Storage A

Cloud schedulers detect this situation and recover.

---

# Example 5: Printer & Scanner

Office Application

↓

Locks Printer

↓

Needs Scanner

Scanner Application

↓

Locks Scanner

↓

Needs Printer

Neither application proceeds.

---

# Example 6: Multiplayer Game Server

Player Session A

↓

Locks Inventory

↓

Needs Trade Database

Player Session B

↓

Locks Trade Database

↓

Needs Inventory

Deadlock delays transactions.

---

# Interview Insight

Question

Where are Deadlocks commonly found?

Answer

- Databases
- Operating Systems
- Cloud Computing
- Banking Systems
- Distributed Systems
- Transaction Processing

---

# Key Takeaways

Deadlocks occur wherever multiple resources are shared among concurrent processes.