# 💻 Java Implementation

## Example 1: synchronized Keyword

```java
class Counter {

    private int count = 0;

    public synchronized void increment() {
        count++;
    }

    public int getCount() {
        return count;
    }
}
```

The `synchronized` keyword ensures that only one thread can execute the `increment()` method at a time.

---

## Example 2: ReentrantLock

```java
import java.util.concurrent.locks.ReentrantLock;

class Counter {

    private int count = 0;
    private final ReentrantLock lock = new ReentrantLock();

    public void increment() {
        lock.lock();
        try {
            count++;
        } finally {
            lock.unlock();
        }
    }
}
```

Advantages:

- Explicit locking and unlocking
- Better control than `synchronized`
- Supports fairness policies

---

## Example 3: Semaphore

```java
import java.util.concurrent.Semaphore;

Semaphore semaphore = new Semaphore(1);

semaphore.acquire();

// Critical Section

semaphore.release();
```

A Binary Semaphore (1 permit) behaves similarly to a mutex by allowing only one thread to enter the critical section.

---

## Interview Questions

- Difference between `synchronized` and `ReentrantLock`?
- What is a Semaphore?
- Difference between Binary Semaphore and Mutex?
- How does Java implement Monitors?
- Why is synchronization necessary?

---

## Google Interview Tip

When asked **"How do you synchronize threads in Java?"**, mention multiple approaches:

- `synchronized`
- `ReentrantLock`
- `Semaphore`
- `ReadWriteLock`
- Atomic Classes (`AtomicInteger`, `AtomicLong`)

This demonstrates practical Java knowledge in addition to Operating System concepts.