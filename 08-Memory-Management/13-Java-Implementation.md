# 💻 Java Implementation

## Example 1: Simple Memory Allocation Simulation

```java
class Process {

    String name;
    int memory;

    Process(String name, int memory) {
        this.name = name;
        this.memory = memory;
    }
}

public class MemoryManager {

    public static void main(String[] args) {

        Process p1 = new Process("Chrome", 200);

        Process p2 = new Process("VS Code", 300);

        Process p3 = new Process("Spotify", 150);

        System.out.println("Allocated Memory:");

        System.out.println(p1.name + " -> " + p1.memory + " MB");

        System.out.println(p2.name + " -> " + p2.memory + " MB");

        System.out.println(p3.name + " -> " + p3.memory + " MB");
    }
}
```

---

## Example 2: First Fit Memory Allocation (Basic)

```java
int[] memory = {100, 500, 200, 300};

int process = 180;

for (int block : memory) {

    if (block >= process) {

        System.out.println("Allocated");

        break;

    }

}
```

---

## Interview Questions

- What is the difference between Heap and Stack?
- How does the JVM manage memory?
- What is Garbage Collection?
- What is Memory Fragmentation?
- How does MMU work?

---

## Google Interview Tip

If asked:

"Explain JVM Memory."

Mention:

- Heap
- Stack
- Method Area
- Program Counter Register
- Native Method Stack

This demonstrates strong Java as well as Operating System knowledge.