# Question 1

### **Question:**

> ***Write a program to Add Two Numbers.***

---------------------------------------
**Solution: **

```python
l=[]
for i in range(2000, 3201):
    if (i%7==0) and (i%5!=0):
        l.append(str(i))

print ','.join(l)
```
----------------------------------------
