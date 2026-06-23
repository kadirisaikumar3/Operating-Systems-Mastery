# 💻 Java Interview Snippets

## Thread Example

```java
class MyThread extends Thread {

    public void run() {

        System.out.println("Thread Running");

    }

}

public class Main {

    public static void main(String[] args) {

        MyThread t = new MyThread();

        t.start();

    }

}
```

---

## Synchronization Example

```java
class Counter {

    synchronized void increment() {

        System.out.println("Safe Access");

    }

}
```

---

## Frequently Asked

- Multithreading
- Synchronization
- JVM Memory
- Thread Lifecycle

---

## Interview Tip

Understand concepts before memorizing answers.