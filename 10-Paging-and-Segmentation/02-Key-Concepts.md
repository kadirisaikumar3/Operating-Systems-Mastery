# 02-Key-Concepts
# 🔑 Key Concepts

## Segmentation

Segmentation divides a program into logical units.

Examples

- Code Segment
- Data Segment
- Stack Segment
- Heap Segment

---

## Segment Table

Stores

- Base Address
- Limit
- Protection Bits

---

## Paging vs Segmentation

| Paging | Segmentation |
|---------|--------------|
| Fixed Size | Variable Size |
| Physical Division | Logical Division |
| Internal Fragmentation | External Fragmentation |

---

## Shared Pages

Multiple processes share common pages.

Example

Shared Libraries

---

## Shared Segments

Processes share logical segments.

Example

Shared Memory.

---

## Address Translation

Paging

Logical Address

↓

Page Number

↓

Frame Number

↓

Physical Address

---

Segmentation

Logical Address

↓

Segment Number

↓

Base Address

↓

Offset

↓

Physical Address

---

## Frequently Asked

- Page Table
- Segment Table
- Address Translation
- Paging vs Segmentation
- Shared Memory

---

## Summary

Paging improves allocation.

Segmentation improves program organization.