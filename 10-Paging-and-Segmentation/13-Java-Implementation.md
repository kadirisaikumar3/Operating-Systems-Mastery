# 💻 Java Implementation

## Example 1: Page Number Calculation

```java
public class Paging {

    public static void main(String[] args) {

        int logicalAddress = 2050;
        int pageSize = 1024;

        int pageNumber = logicalAddress / pageSize;
        int offset = logicalAddress % pageSize;

        System.out.println("Page Number : " + pageNumber);
        System.out.println("Offset : " + offset);

    }

}
```

---

## Example 2: Segment Representation

```java
class Segment {

    String name;
    int base;
    int limit;

    Segment(String name,int base,int limit){

        this.name=name;
        this.base=base;
        this.limit=limit;

    }

}
```

---

## Interview Questions

- What is Paging?
- What is Segmentation?
- Paging vs Segmentation?
- Internal vs External Fragmentation?
- How does Address Translation work?

---

## Google Interview Tip

Always compare

Paging

↓

Segmentation

↓

Virtual Memory

↓

MMU

This is a common whiteboard discussion.