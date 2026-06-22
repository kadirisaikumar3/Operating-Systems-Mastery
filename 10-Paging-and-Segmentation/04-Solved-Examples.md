# 04-Solved-Examples
# ✅ Solved Examples

---

# Example 1

## Paging

Logical Address

```
2500
```

Page Size

```
1024 Bytes
```

Page Number

```
2500 / 1024 = 2
```

Offset

```
2500 % 1024 = 452
```

Final

Page = 2

Offset = 452

---

# Example 2

## Address Translation

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

# Example 3

## Segmentation

Segment Table

| Segment | Base | Limit |
|----------|------|------|
| Code | 1000 | 500 |
| Data | 2000 | 300 |
| Stack | 3000 | 400 |

Logical Address

(Code,120)

Physical Address

```
1000 + 120

=

1120
```

---

# Example 4

## Internal Fragmentation

Frame Size

```
1024 Bytes
```

Program

```
1000 Bytes
```

Unused

```
24 Bytes
```

---

# Example 5

## External Fragmentation

Memory

100 MB

↓

50 MB Free

↓

100 MB Used

↓

60 MB Free

↓

Process

80 MB

Cannot allocate because free memory is fragmented.

---

# Google Tip

Always calculate

Page Number

Offset

Frame Number

before answering.