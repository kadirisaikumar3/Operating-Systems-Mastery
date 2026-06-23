# 01-Concepts
# 📚 System Call Concepts

## What is a System Call?

A System Call is a mechanism through which a user program requests services from the Operating System kernel.

---

## Why are System Calls Needed?

Applications cannot directly access:

- CPU Resources
- Memory
- Files
- Devices

The Operating System controls these resources.

---

## Basic Flow

User Program

↓

System Call

↓

Kernel

↓

Hardware

↓

Result Returned

---

## Example

Opening a file

Application

↓

open()

↓

Kernel

↓

Disk Access

↓

File Descriptor Returned

---

## Goals

- Security
- Resource Management
- Hardware Abstraction
- Process Management

---

## User Mode

Restricted Mode

Cannot access hardware directly.

---

## Kernel Mode

Privileged Mode

Can access all system resources.

---

## Interview Tip

Remember

User Mode

↓

System Call

↓

Kernel Mode

↓

Service Execution# 📚 System Call Concepts

## What is a System Call?

A System Call is a mechanism through which a user program requests services from the Operating System kernel.

---

## Why are System Calls Needed?

Applications cannot directly access:

- CPU Resources
- Memory
- Files
- Devices

The Operating System controls these resources.

---

## Basic Flow

User Program

↓

System Call

↓

Kernel

↓

Hardware

↓

Result Returned

---

## Example

Opening a file

Application

↓

open()

↓

Kernel

↓

Disk Access

↓

File Descriptor Returned

---

## Goals

- Security
- Resource Management
- Hardware Abstraction
- Process Management

---

## User Mode

Restricted Mode

Cannot access hardware directly.

---

## Kernel Mode

Privileged Mode

Can access all system resources.

---

## Interview Tip

Remember

User Mode

↓

System Call

↓

Kernel Mode

↓

Service Execution