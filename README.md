# codeFamilyFued

## Trivia



## Variables
- What data type is "True"
- What data type is "7"
- Describe a boolean
- Describe a String
- Describe an Integer



### What is the output
```
x = 3
y = x
x = 4
print(y)
```

## Output/Functions
```
Write a function that prints whether a number is even or odd
def checkEven(x):
  if x % 2 == 0:
    print("Number is even")
  else:
    print("Number is odd")
```

## Arrays
```
print the second number in this list

x = [3,6,9,10]
```
```
Write a program that checks whether the integer 5 is an element in a list. Assume the list is called x

for number in x:
  if number == 5:
    print("Weve found it")
  else:
    print("its not here")




```


```
How would I add a number to the end of this list?

x = [7,4,7,11]

x.append(5)
```

## Loops
```
Given a list X. Write a loop that prints every integer one at a time

For number in x:
  print(number)
```

```
Make a loop that counts from  to 100

x = 0
while x <101:
  print(x)
  x +=1
```

## Conditionals
```
"""
3.Question 3
What’s the output of this code if number equals 10?
"""

if number > 11: 
  print(0)
elif number != 10:
  print(1)
elif number >= 20 or number < 12:
  print(2)
else:
  print(3)
  
```
```

```
## Logic Problems
```
At McDonalds one can buy chicken nuggets in packages containing 6, 9 or 20 pieces.  Write a 
Python function that accepts an integer, num, as an argument and decides whether or not it is 
possible to buy num nuggets at McDonalds
```
```
Write a function, add_it_up(), that takes a single integer as input and 
returns the sum of the integers from zero to the input parameter.


def better(n):
    sum = 0
    for num in range(n + 1):
        sum += num
    return sum
```
```
Given two integer numbers return their product only if the product is greater than 1000, else return their sum.

if x*y > 1000:
  return x*y
 else:
  return x+y
```

```
Given 2 ints, a and b, return True if one if them is 10 or if their sum is 10.

makes10(9, 10) → True
makes10(9, 9) → False
makes10(1, 9) → True


if a == 10 or b == 10:
  return True
elif a + b == 10:
  return True
```
```
At the time of this writing, a US Dollar is worth 0.73 British Pounds. For this assignment, 
create a conversion program that prompts the user to enter how many US Dollars they have. 
Then, provide the conversion to British Pounds and then to Bison Dollars.
```

```
Create a function that accepts a measurement value in inches and returns the equivalent of the measurement value in feet.

def convert(inches):
  return inches/12
```
```


```
