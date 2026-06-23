# 💻 Java Implementation

## Simulating Device Input

```java
import java.util.Scanner;

public class InputExample {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.print("Enter Name: ");

        String name = sc.nextLine();

        System.out.println("Hello " + name);

    }

}
```

---

## File Output Example

```java
import java.io.FileWriter;

public class OutputExample {

    public static void main(String[] args) throws Exception {

        FileWriter writer = new FileWriter("output.txt");

        writer.write("Operating Systems");

        writer.close();

    }

}
```

---

## Google Interview Questions

- What is DMA?
- Programmed I/O vs Interrupt I/O?
- What is a Device Driver?
- What is a Device Controller?

---

## Google Interview Tip

Always compare:

Programmed I/O

↓

Interrupt-Driven I/O

↓

DMA