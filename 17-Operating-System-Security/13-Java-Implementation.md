# 💻 Java Implementation

## Password Validation Example

```java
public class PasswordCheck {

    public static void main(String[] args) {

        String password = "Admin123";

        if(password.length() >= 8){

            System.out.println("Strong Password");

        } else {

            System.out.println("Weak Password");

        }

    }

}
```

---

## Hashing Example

```java
import java.security.MessageDigest;

public class HashExample {

    public static void main(String[] args)
            throws Exception {

        MessageDigest md =
                MessageDigest.getInstance("SHA-256");

        byte[] hash =
                md.digest("password".getBytes());

        System.out.println(hash.length);

    }

}
```

---

## Google Interview Questions

- What is CIA Triad?
- Authentication vs Authorization?
- What is Encryption?
- What is Firewall?

---

## Interview Tip

Always compare:

Authentication

↓

Authorization

↓

Access Control