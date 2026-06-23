# 02-Key-Concepts
# 🔑 Key Concepts

## Shared Memory

Processes share a common memory region.

Advantages

- Fastest IPC

Disadvantages

- Requires Synchronization

---

## Message Passing

Processes communicate using messages.

Advantages

- Simple
- Secure

Disadvantages

- Slower than Shared Memory

---

## Pipes

Used between related processes.

Characteristics

- Half Duplex
- Parent Child Communication

---

## Named Pipes (FIFO)

Special file-based communication.

Can be used by unrelated processes.

---

## Sockets

Used for network communication.

Examples

- Web Applications
- Client Server Systems

---

## Signals

Used to notify processes about events.

Examples

- SIGINT
- SIGTERM

---

## Semaphores

Used for synchronization.

Prevent race conditions.

---

## Frequently Asked

- Shared Memory
- Message Passing
- Pipes
- Sockets
- Semaphores

---

## Summary

Shared Memory is fastest.

Sockets are most flexible.