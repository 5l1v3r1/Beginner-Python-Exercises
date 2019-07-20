# Question 1

### **Question:**

> ***Write a program to Add Two Numbers.***

---------------------------------------

<strong>Solution: </strong>

```python
a = 1
b = 2
c= a+b
print(c)
```
----------------------------------------

```python
a = int(input("enter a number: "))
b = int(input("enter a number: "))
c= a+b
print(c)
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

# Question 3

### **Question:**

> ***Write a program to check whether a number entered by the user is positive, negative or zero.***

---------------------------------------

<strong>Solution: </strong>

```python
a = int(input("Enter a number: "))
if a > 0:
   print("Positive number")
elif a == 0:
   print("Zero")
else:
   print("Negative number")
```
----------------------------------------

# Question 4

### **Question:**

> ***Write a program to display the calendar of a given date.***

---------------------------------------

<strong>Solution: </strong>

```python
import calendar
yy = int(input("Enter year: "))
mm = int(input("Enter month: "))
print(calendar.month(yy, mm))
```
----------------------------------------

# Question 5

### **Question:**

> ***Write a program to ask the user to enter the string and print that string as output of the program.***

---------------------------------------

<strong>Solution: </strong>

```python
string = input("Enter string: ")
print("You entered:",string)
```
----------------------------------------

# Question 6

### **Question:**

> ***Write a program to Concatenate Two Strings.***

---------------------------------------

<strong>Solution: </strong>

```python
string1 = input("Enter first string to concatenate: ")
string2 = input("Enter second string to concatenate: ")
string3 = string1 + string2
print("String after concatenation = ",string3)
```
----------------------------------------

# Question 7

### **Question:**

> ***Write a program to Check if an item exists in the list.***

---------------------------------------

<strong>Solution: </strong>

```python
list_of_items = ["ball", "book", "pencil"]
item = input("Type item to check: ")
if item in list_of_items:
 print("Item exists in the list.")
else:
  print("Item does not exist in the list.") 
```
----------------------------------------

# Question 8

### **Question:**

> ***Write a program to Join two or more lists.***

---------------------------------------

<strong>Solution: </strong>

```python
list1 = ["This" , "is", "a", "sample", "program"]
list2 = [10, 2, 45, 3, 5, 7, 8, 10]
finalList = list1 + list2
print(finalList) 
```
----------------------------------------

# Question 9

### **Question:**

> ***Write a program to Calculate Cube of a Number.***

---------------------------------------

<strong>Solution: </strong>

```python
import math 
a = int(input("Enter a number: "))
b=math.pow(a,3)
print (b) 
```
----------------------------------------










