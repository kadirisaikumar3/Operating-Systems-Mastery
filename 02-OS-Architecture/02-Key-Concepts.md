# 02-Key-Concepts
# 🔑 Key Concepts

Before learning different Operating System Architectures, understand these important concepts.

---

# Kernel

The Kernel is the core of the Operating System.

Responsibilities:

- Process Management
- Memory Management
- File Management
- Device Communication
- CPU Scheduling

---

# User Space

Applications execute here.

Examples:

- Chrome
- VS Code
- Spotify

User Space cannot directly access hardware.

---

# Kernel Space

Kernel executes here.

It has complete control over:

- CPU
- Memory
- Storage
- Devices

---

# System Calls

Applications communicate with the Kernel using System Calls.

Example:

```

Application

↓

System Call

↓

Kernel

↓

Hardware

```

---

# Device Drivers

Device Drivers enable communication between hardware and Operating System.

Examples:

- Printer Driver
- GPU Driver
- Audio Driver
- Network Driver

---

# Different Kernel Architectures

### Monolithic Kernel

Everything runs inside the Kernel.

Examples:

- Linux
- UNIX

Advantages

- Fast

Disadvantages

- Large Kernel

---

### Microkernel

Only essential services remain inside Kernel.

Examples:

- MINIX
- QNX

Advantages

- Secure
- Reliable

Disadvantages

- Slightly Slower

---

### Hybrid Kernel

Combination of Monolithic and Microkernel.

Examples

- Windows NT
- macOS

Advantages

- Performance
- Flexibility

---

### Layered Architecture

Operating System divided into multiple layers.

Each layer communicates only with adjacent layers.

Advantages

- Easy Maintenance
- Better Modularity

---

### Modular Kernel

Kernel supports dynamically loadable modules.

Example

Linux Kernel Modules

Advantages

- Flexible
- Extensible

---

### Exokernel

Provides minimal abstraction over hardware.

Applications manage resources directly.

Mostly used in research.

---

### Nanokernel

Extremely small Kernel.

Used in embedded systems.

---

# Interview Tips

Frequently Asked

- Difference between Monolithic and Microkernel?
- Why Windows uses Hybrid Kernel?
- Why Linux is called Monolithic?
- Kernel Space vs User Space?
- What are System Calls?

---

# Summary

Understanding these concepts makes learning Processes, Scheduling, Memory Management and System Calls much easier.