# 💻 Java Implementation

## File Read Example

```java
import java.io.*;

public class ReadFile {

    public static void main(String[] args) throws Exception {

        BufferedReader br =
                new BufferedReader(
                new FileReader("sample.txt"));

        String line;

        while((line = br.readLine()) != null){

            System.out.println(line);

        }

        br.close();

    }

}
```

---

## Process Example

```java
public class ProcessExample {

    public static void main(String[] args)
            throws Exception {

        Runtime.getRuntime()
                .exec("notepad");

    }

}
```

---

## Google Interview Questions

- What is a System Call?
- User Mode vs Kernel Mode?
- What is fork()?
- What is exec()?
- What is open()?

---

## Interview Tip

Always explain

User Program

↓

System Call

↓

Kernel

↓

Hardware