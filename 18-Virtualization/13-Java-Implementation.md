# 💻 Java Implementation

## System Information Example

```java
public class VMInfo {

    public static void main(String[] args) {

        System.out.println(
            Runtime.getRuntime().availableProcessors());

        System.out.println(
            Runtime.getRuntime().maxMemory());

    }

}
```

---

## Thread Example

```java
public class VirtualThreadDemo {

    public static void main(String[] args) {

        Thread t = new Thread(() ->
                System.out.println("Running"));

        t.start();

    }

}
```

---

## Google Interview Questions

- What is Virtualization?
- What is a Hypervisor?
- VM vs Container?
- Docker vs Virtual Machine?

---

## Interview Tip

Always compare

Type 1

↓

Type 2

↓

VM

↓

Container