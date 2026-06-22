# 💻 Java Implementation

## Example 1: Deadlock Example

```java
public class DeadlockExample {

    private static final Object lock1 = new Object();
    private static final Object lock2 = new Object();

    public static void main(String[] args) {

        Thread t1 = new Thread(() -> {

            synchronized(lock1) {

                System.out.println("Thread 1 locked Lock1");

                synchronized(lock2) {

                    System.out.println("Thread 1 locked Lock2");

                }

            }

        });

        Thread t2 = new Thread(() -> {

            synchronized(lock2) {

                System.out.println("Thread 2 locked Lock2");

                synchronized(lock1) {

                    System.out.println("Thread 2 locked Lock1");

                }

            }

        });

        t1.start();

        t2.start();
    }
}
```

This program may enter a deadlock because each thread acquires the locks in a different order.

---

## Deadlock Prevention

Acquire locks in a consistent order.

Example:

```
Always lock:

lock1

↓

lock2
```

---

## Using ReentrantLock

```java
ReentrantLock lock = new ReentrantLock();

lock.lock();

try{

    // Critical Section

}
finally{

    lock.unlock();

}
```

---

## Interview Questions

- How does Java detect deadlocks?
- How can deadlocks be prevented?
- Why does lock ordering prevent deadlocks?
- Difference between synchronized and ReentrantLock?

---

## Google Interview Tip

When asked:

"How do you prevent Deadlocks?"

Mention

- Lock Ordering
- Timeout
- tryLock()
- Avoid Nested Locks
- Resource Hierarchy