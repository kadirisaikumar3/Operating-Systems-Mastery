# 03-Real-World-Example
# 🌍 Real-World Examples

System Calls are used whenever applications interact with the Operating System.

---

# Example 1: Opening a File

User opens a PDF.

↓

Application calls

open()

↓

Kernel accesses disk.

↓

File returned to application.

---

# Example 2: Saving a Document

User clicks Save.

↓

write()

↓

Kernel writes data to storage.

↓

Document saved.

---

# Example 3: Creating a Process

Chrome opens a new tab.

↓

fork()

↓

New process created.

↓

exec()

↓

Program loaded.

---

# Example 4: Internet Browsing

Browser accesses website.

↓

socket()

↓

send()

↓

recv()

↓

Webpage displayed.

---

# Example 5: Mobile Applications

App requests camera access.

↓

System Call

↓

Kernel validates permission.

↓

Camera enabled.

---

# Example 6: Cloud Systems

Cloud services create thousands of processes.

System Calls manage

- Files
- Processes
- Networking
- Security

---

# Interview Insight

Question

Where are System Calls used?

Answer

- Browsers
- Databases
- Mobile Apps
- Cloud Platforms
- Operating Systems

---

# Key Takeaways

Every interaction with OS resources eventually uses System Calls.