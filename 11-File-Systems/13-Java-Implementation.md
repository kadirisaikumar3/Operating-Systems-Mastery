# 💻 Java Implementation

## Example 1: Create a File

```java
import java.io.File;
import java.io.IOException;

public class CreateFileExample {

    public static void main(String[] args) throws IOException {

        File file = new File("sample.txt");

        if(file.createNewFile()){

            System.out.println("File Created");

        } else {

            System.out.println("File Already Exists");

        }

    }

}
```

---

## Example 2: Read File Information

```java
import java.io.File;

public class FileInfo {

    public static void main(String[] args) {

        File file = new File("sample.txt");

        System.out.println(file.getName());

        System.out.println(file.length());

        System.out.println(file.canRead());

        System.out.println(file.canWrite());

    }

}
```

---

## Google Interview Questions

- What is a File System?
- FAT vs NTFS?
- What is an Inode?
- Hard Link vs Soft Link?
- Sequential vs Direct Access?

---

## Google Interview Tip

When explaining File Systems, always compare:

- FAT
- NTFS
- ext4

This comparison is frequently asked in interviews.