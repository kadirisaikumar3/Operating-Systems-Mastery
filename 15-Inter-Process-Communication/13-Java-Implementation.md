# 💻 Java Implementation

## Thread Communication Example

```java
class SharedData {

    int value;

}

public class IPCExample {

    public static void main(String[] args) {

        SharedData data = new SharedData();

        data.value = 100;

        System.out.println(data.value);

    }

}
```

---

## Socket Example

```java
import java.net.Socket;

public class SocketExample {

    public static void main(String[] args)
            throws Exception {

        Socket socket =
                new Socket("localhost",8080);

        System.out.println("Connected");

        socket.close();

    }

}
```

---

## Google Interview Questions

- What is IPC?
- Shared Memory vs Message Passing?
- Pipes vs Sockets?
- What is a Semaphore?

---

## Interview Tip

Always compare

Shared Memory

↓

Message Passing

↓

Sockets