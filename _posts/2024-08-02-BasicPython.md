---
title: BasicPython
author: Haosheng Wu
date: 2024-08-02
category: Jekyll
layout: post
---

In this page, we will introduce the simplest usages of Python, which are used in this workshop. You can also try the following python commands in the Jupyter notebook from our pex2024 docker container or an [online python interpreter](https://onecompiler.com/python).<br>

## 1. Print 'Hello World!'

The first example is print 'Hello World!' in python. The command is:

```markdown
print("Hello, World!")
```
In Python, print() is a function used to display text, variables, calculation results, and other information. 
Some other examples are: 

```markdown
name = "Haosheng.Wu"
score = 18
print(name, score)
```

## 2. Simple calculation

In Python, you can easily perform simple calculations using basic arithmetic operators. Here are some examples:

```markdown
# Addition
a = 2
b = 3 
c = a + b
print("c =", c)

# Subtraction
a = 10
b = 4
c = 10 - 4
print("c=", c)

# Multiplication
a = 5
b = 6
c = 5 * 6
print("c =", c)

# Division
a = 20
b = 3
c = a/b
print("c=", c)
```

## 3. Function

In Python, a function is a block of reusable code that performs a specific task. In the workshop, we will not write any function, but may use some function already exist.

```markdown
def add(a, b):
    return a + b

sum = add(5, 7)
print("The sum is:", sum)
```

## 4. Array

In Python, there are good open source libraries, Numpy is one of them which can be used to create 2D array. Following is an example of 2D array with size a(5,2).

```markdown
# Import the numpy library as the name of np
import numpy as np

# Use np.array create a 5*2 array that has the format array[row_index, column_index]
# The index is start from 0.
array = np.array([[1,2],[3,4],[5,6],[7,8],[9,10]])

# Print each row
print(array[0,:])
print(array[1,:])
print(array[2,:])
print(array[3,:])
print(array[4,:])

# Print each column
print(array[:,0])
print(array[:,1])
```

## 5. Power and Square of an array

```markdown
# Import the numpy library as the name of np
import numpy as np

array = np.array([1, 2, 3, 4, 5, 6])

# Calculate square
power_array = np.power(array,2)
print(power_array)

# Calculate square root
square_array = np.power(power_array, 0.5)
print(square_array)
```