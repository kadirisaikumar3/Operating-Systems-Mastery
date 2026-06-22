# 💻 Java Implementation

## Example: FIFO Page Replacement Simulation

```java
import java.util.*;

public class FIFOPageReplacement {

    public static void main(String[] args) {

        int[] pages = {7,0,1,2,0,3,0,4};
        int frames = 3;

        Queue<Integer> queue = new LinkedList<>();
        Set<Integer> memory = new HashSet<>();

        int pageFaults = 0;

        for(int page : pages){

            if(!memory.contains(page)){

                pageFaults++;

                if(memory.size() == frames){

                    int removed = queue.poll();

                    memory.remove(removed);

                }

                queue.offer(page);

                memory.add(page);

            }

        }

        System.out.println("Page Faults : " + pageFaults);

    }

}
```

---

## Interview Questions

- What is Virtual Memory?
- What is Demand Paging?
- Explain FIFO.
- Explain LRU.
- Explain Thrashing.
- Explain Copy-on-Write.

---

## Google Interview Tip

When discussing Virtual Memory, compare page replacement algorithms:

- FIFO
- LRU
- Optimal
- Clock

Also mention their advantages and disadvantages.