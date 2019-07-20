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

# Question 10

### **Question:**

> ***Write a program to Calculate Square root of a Number.***

---------------------------------------

<strong>Solution: </strong>

```python
import math 
a = int(input("Enter a number: "))
b=math.sqrt(a)
print (b)  
```
----------------------------------------

# Question 11

### **Question:**

> ***Write a program that takes a list of numbers (for example, a = [5, 10, 15, 20, 25]) and makes a new list of only the first and last elements of the given list.***

---------------------------------------

<strong>Solution: </strong>

```python
a = [5, 10, 15, 20, 25]
print([a[0], a[4]]) 
```
----------------------------------------

# Question 12

### **Question:**

> ***Take a list, say for example this one: a = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89] and write a program that prints out all the elements of the list that are less than 5.***

---------------------------------------

<strong>Solution: </strong>

```python
a = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]
for i in a:
    if i < 5:
        print(i)
```
----------------------------------------


# Question 13

### **Question:**

> ***Let's say I give you a list saved in a variable: a = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]. Write one line of Python that takes this list 'a' and makes a new list that has only the even elements of this list in it.***

---------------------------------------

<strong>Solution: </strong>

```python
a = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
b = [number for number in a if number % 2 == 0]
print(b)
```
----------------------------------------

# Question 14

### **Question:**

> ***Ask the user for a string and print out whether this string is a palindrome or not (A palindrome is a string that reads the same forwards and backwards).***

---------------------------------------

<strong>Solution: </strong>

```python
a=input("Please enter a word: ")
c = a.casefold()
b = reversed(c)
if list(c) == list(b):
   print("It is palindrome")
else:
   print("It is not palindrome")
```
----------------------------------------

# Question 15

### **Question:**

> ***Take two lists, say for example these two: a = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89] b = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13] and write a program that returns a list that contains only the elements that are common between the lists (without duplicates). Make sure your program works on two lists of different sizes.***

---------------------------------------

<strong>Solution: </strong>

```python
a = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]
b = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13]
result = [i for i in set(a) if i in b]
print(result)
```
----------------------------------------

# Question 16

### **Question:**

> ***Write a program to add a string to text file.***

---------------------------------------

<strong>Solution: </strong>

```python
file = open("testfile.txt","w") 
file.write("Hello World") 
file.write("This is our new text file") 
file.write("and this is another line.") 
file.write("Why? Because we can.") 
file.close()
```
----------------------------------------

# Question 17

### **Question:**

> ***Write a program to read a file and display its contents on console.***

---------------------------------------

<strong>Solution: </strong>

```python
with open('testfile.txt') as f:
  	line = f.readline()
  	while line:
  		print(line)
  		line = f.readline()
```
----------------------------------------

# Question 18

### **Question:**

> ***Take two sets, say for example these two: a = {1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89} b = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13} and write a program that returns a set that contains only the elements that are common between the sets.***

---------------------------------------

<strong>Solution: </strong>

```python
a = {1, 1, 2, 2, 3, 5, 8, 13, 21, 34, 55, 89}
b = {1, 2, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13}
c = set(a) & set(b)  
print(c)
```
----------------------------------------

# Question 19

### **Question:**

> ***Write a program to split the characters of the given string into a list.***

---------------------------------------

<strong>Solution: </strong>

```python
s = "mystring"
l = list(s)
print (l)
```
----------------------------------------

# Question 20

### **Question:**

> ***Create a program that asks the user for a number and then prints out a list of all the divisors of that number.***

---------------------------------------

<strong>Solution: </strong>

```python
n=int(input("Enter an integer: "))
print("The divisors of the number are: ")
for i in range(1,n+1):
    if(n%i==0):
        print(i)
```
----------------------------------------

# Question 21

### **Question:**

> ***Write a program to Find the largest of three numbers.***

---------------------------------------

<strong>Solution: </strong>

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))
if (a > b) and (a > c):
   largest = a
elif (b > a) and (b > c):
   largest = b
else:
   largest = c
print("The largest number is", largest)
```
----------------------------------------

# Question 22

### **Question:**

> ***Write a Program to Find Absolute value of a Number.***

---------------------------------------

<strong>Solution: </strong>

```python
num = int(input("Enter a number: "))
if num >= 0:
		print(num)
else:
		print(-num)
```
----------------------------------------

# Question 23

### **Question:**

> ***Write a program to Find the length of a String.***

---------------------------------------

<strong>Solution: </strong>

```python
print("Enter 'y' for exit.")
string = input("Enter a string: ")
if string == 'y':
    exit()
else:
    print("Length of the string =", len(string))
```
----------------------------------------

# Question 24

### **Question:**

> ***Write a program to Print Natural Numbers from 1 to N.***

---------------------------------------

<strong>Solution: </strong>

```python
N = int(input("Please Enter any Number: "))
for i in range(1, N+1):
    print (i)
```
----------------------------------------


# Question 25

### **Question:**

> ***Write a program to calculate the sum and average of Natural Numbers from 1 to N.***

---------------------------------------

<strong>Solution: </strong>

```python
N = int(input("Please Enter any Number: "))
sum = 0
for i in range(1,N+1):
  sum = sum + i
print(sum)
average = sum / N
print(average)
```
----------------------------------------


# Question 26

### **Question:**

> ***Write a program to Print a Statement Any Number of Times.***

---------------------------------------

<strong>Solution: </strong>

```python
n = int(input("Please Enter any Number: "))
for i in range(n):
    print("hello world")
```
----------------------------------------

# Question 27

### **Question:**

> ***Write a program To Multiply Two Numbers Using Function.***

---------------------------------------

<strong>Solution: </strong>

```python
def my_function():
    a = int(input("enter a number: "))
    b=int(input("enter a number: "))
    c= a*b
    return c
d = my_function()
print (d)
```
----------------------------------------

# Question 28

### **Question:**

> ***Write a program To add an item to the end of the list.***

---------------------------------------

<strong>Solution: </strong>

```python
list1 = ["pen", "book", "ball"]
list1.append("bat")
print(list1)
```
----------------------------------------
