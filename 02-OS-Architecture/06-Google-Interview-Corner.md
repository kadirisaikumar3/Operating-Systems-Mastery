# 06-Google-Interview-Corner
# 🚀 Google Interview Corner

This section contains conceptual questions commonly asked in Google, Microsoft, Amazon, Apple, Adobe, Atlassian and other Product-Based Company interviews.

---

# Question 1

What is Operating System Architecture?

Expected Answer:

It defines the internal structure and organization of an Operating System, explaining how different components interact with hardware and applications.

---

# Question 2

Why is Linux called a Monolithic Kernel?

Expected Points

- Core services execute inside Kernel Space.
- Fast communication.
- High performance.

---

# Question 3

Why is Windows called a Hybrid Kernel?

Expected Points

- Combination of Monolithic + Microkernel.
- Better compatibility.
- Good performance.
- Improved modularity.

---

# Question 4

Monolithic vs Microkernel

| Monolithic | Microkernel |
|-------------|-------------|
| Fast | Secure |
| Large Kernel | Small Kernel |
| Less Modular | Highly Modular |
| Higher Performance | Better Reliability |

---

# Question 5

User Space vs Kernel Space

| User Space | Kernel Space |
|------------|--------------|
| Applications | Operating System |
| Limited Access | Full Hardware Access |
| Safe | Privileged |

---

# Question 6

Explain what happens when Chrome reads a file.

Expected Flow

Chrome

↓

System Call

↓

Kernel

↓

File System

↓

Disk

↓

Kernel

↓

Chrome

---

# Question 7

Which architecture would you recommend for:

- Banking Server
- Air Traffic Control
- Smart Watch
- Gaming PC

Explain your reasoning.

---

# Google Interview Tip

Google interviewers usually ask:

> "Why?"

Always justify your answer instead of memorizing definitions.

Example:

Question:

Why does Linux use Monolithic Architecture?

Good Answer:

Because Monolithic Kernels execute all services inside Kernel Space, resulting in faster communication and better performance.
