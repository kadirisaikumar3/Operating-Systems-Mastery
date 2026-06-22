# 06-Google-Interview-Corner
# 🚀 Google Interview Corner

File Systems are commonly asked in Operating System interviews.

---

# Question 1

What is a File System?

Expected Answer

A File System organizes, stores, retrieves, and protects files on secondary storage.

---

# Question 2

NTFS vs FAT

| FAT | NTFS |
|------|------|
| Older | Modern |
| No Journaling | Journaling |
| Small Files | Large Files |
| Limited Security | Advanced Security |

---

# Question 3

Hard Link vs Soft Link

| Hard Link | Soft Link |
|-----------|-----------|
| Points to Inode | Points to File Path |
| Cannot cross file systems | Can cross file systems |
| Original file deletion doesn't remove data | Broken if original file is deleted |

---

# Question 4

File Allocation Methods

- Contiguous
- Linked
- Indexed

Know their advantages and disadvantages.

---

# Question 5

What is an Inode?

Expected Answer

An inode stores metadata about a file, such as permissions, owner, timestamps, size, and pointers to data blocks.

---

# Google Follow-up Questions

Interviewer

What is a File System?

↓

How does NTFS differ from ext4?

↓

What is Journaling?

↓

What is an Inode?

↓

Hard Link vs Soft Link?

↓

Which allocation method is fastest?

---

# Google Interview Tip

Always compare

FAT

↓

NTFS

↓

ext4

Interviewers often ask for practical differences rather than definitions.