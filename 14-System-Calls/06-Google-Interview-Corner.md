# 06-Google-Interview-Corner
# 🚀 Google Interview Corner

System Calls are among the most frequently asked OS concepts.

---

# Question 1

What is a System Call?

Expected Answer

A System Call is an interface through which user programs request services from the Operating System kernel.

---

# Question 2

User Mode vs Kernel Mode

| User Mode | Kernel Mode |
|------------|------------|
| Limited Access | Full Access |
| Safe | Privileged |
| Cannot Access Hardware Directly | Can Access Hardware |

---

# Question 3

What happens when open() is called?

Expected Answer

Application

↓

System Call

↓

Kernel checks file

↓

File Descriptor returned

---

# Question 4

What is fork()?

Expected Answer

fork() creates a new child process.

---

# Question 5

What is exec()?

Expected Answer

exec() replaces the current process image with a new program.

---

# Google Follow-up Questions

Interviewer

What is a System Call?

↓

Why do we need it?

↓

User Mode?

↓

Kernel Mode?

↓

fork()?

↓

exec()?

↓

wait()?

↓

socket()?

---

# Google Interview Tip

Always explain:

User Program

↓

System Call Interface

↓

Kernel

↓

Hardware