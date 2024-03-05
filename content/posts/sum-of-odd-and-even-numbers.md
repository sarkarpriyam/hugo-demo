---
title: 'Sum of Odd and Even Numbers'
date: 2024-03-05T22:45:56+05:30
draft: false
---
```
number = input("Enter the number ")
even_sum = 0
odd_sum = 0
for digit in number:
    if int(digit)%2 == 0:
        even_sum += int(digit)
    else:
        odd_sum += int(digit)


print("Even sum %d" % even_sum)
print("Odd sum %d" % odd_sum)
```
