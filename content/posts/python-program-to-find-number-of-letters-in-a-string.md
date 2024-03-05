---
title: 'Python Program to Find Number of Letters in a String'
date: 2024-03-05T22:31:29+05:30
draft: false
---

```
string1 = input("Enter the string ")  
d = {}  
for char in string1: 
    if char not in d:  
    d["char"] = 1  
else:
    d["char"] += 1
print(d)
```

