# Question 1

### **Question:**

> ***Write a program to Add Two Numbers.***

---------------------------------------

<strong>Solution: </strong>

```python
def my_function(a,b):
    c= a+b
    return c
d = my_function(1,2)
print (d)
```
----------------------------------------

```python
def my_function():
    a = int(input("enter a number: "))
    b=int(input("enter a number: "))
    c= a+b
    return c
d = my_function()
print (d)

```
----------------------------------------

# Question 2

### **Question:**

> ***Write a program to find whether a given number (accept from the user) is even or odd, print out an appropriate message to the user.***

---------------------------------------

<strong>Solution: </strong>

```python
a = int(input("enter a number: "))
if a % 2 == 0:
    print("This is an even number.")
else:
    print("This is an odd number.")
```
----------------------------------------


