# 09-Cheat-Sheet
# 📋 Paging & Segmentation Cheat Sheet

## Paging Flow

CPU

↓

Logical Address

↓

Page Number

↓

Page Table

↓

Frame Number

↓

Physical Address

---

## Segmentation Flow

CPU

↓

Logical Address

↓

Segment Number

↓

Segment Table

↓

Base + Offset

↓

Physical Address

---

## Comparison

| Paging | Segmentation |
|---------|--------------|
| Fixed Size | Variable Size |
| Page Table | Segment Table |
| Internal Fragmentation | External Fragmentation |

---

## Google Tip

Always explain

Logical Address

↓

Translation

↓

Physical Address