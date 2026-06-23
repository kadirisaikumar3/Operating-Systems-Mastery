# 💻 Java Implementation

## Execute Linux Command

```java
import java.io.*;

public class LinuxCommand {

    public static void main(String[] args)
            throws Exception {

        Process process =
                Runtime.getRuntime()
                .exec("ls");

        BufferedReader br =
                new BufferedReader(
                new InputStreamReader(
                process.getInputStream()));

        String line;

        while((line = br.readLine()) != null){

            System.out.println(line);

        }

    }

}
```

---

## Process Information Example

```java
public class ProcessInfo {

    public static void main(String[] args) {

        System.out.println(
                ProcessHandle.current().pid());

    }

}
```

---

## Google Interview Questions

- What is Linux?
- What is the Linux Kernel?
- Explain Linux Architecture.
- What are Linux Permissions?

---

## Interview Tip

Always explain:

User Space

↓

System Calls

↓

Kernel Space