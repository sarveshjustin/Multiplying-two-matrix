# Multiplying-two-matrix

## AIM:
To write a python program to multiply two arrays using numpy.

## ALGORITHM:
Step 1:
Importing numpy module.

Step 2:
Get the input from user.

Step 3:
Create a empty list l1 and l2.

Step 4:
Use for loop to append the values into the list created.

Step 5:
Print the product of two arrays .


## PROGRAM: 

Developed by:sarvesh.s

RegisterNumber: 22003029
```
import numpy as np
l1,l2=[],[]
n= int(input())
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
value1=np.array(l1)
value2=np.array(l2)
result=value1*value2
print("Product of two arrays is:",result)
```

## OUTPUT:
![output](./ren.png)

## RESULT:
A python program to multiply two arrays using numpy is written.

