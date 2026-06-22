# 📋 Operating System Architecture Cheat Sheet

## Architecture Flow

```

Applications

↓

System Calls

↓

Kernel

↓

Hardware

```

---

## Architecture Comparison

| Architecture | Performance | Security | Example |
|--------------|------------|----------|---------|
| Monolithic | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ | Linux |
| Microkernel | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | MINIX |
| Hybrid | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | Windows |
| Layered | ⭐⭐⭐ | ⭐⭐⭐⭐ | THE OS |
| Modular | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | Linux Modules |

---

## Common Examples

| OS | Architecture |
|----|-------------|
| Linux | Monolithic |
| Windows | Hybrid |
| macOS | Hybrid |
| Android | Linux Kernel |
| QNX | Microkernel |

---

## Remember

Kernel

↓

System Calls

↓

Hardware

Applications never directly communicate with Hardware.

---

## Google Interview Tip

Always compare

Performance

↓

Security

↓

Maintainability

↓

Scalability

instead of only definitions.