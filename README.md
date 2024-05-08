# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print' .

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4.  print the variable 'X' 

## Program:
(i) To find the L and U matrix

'''
Program to find L and U matrix using LU decomposition.
Developed by: t. Gayathri
RegisterNumber: 212223100007
```
```
import numpy as np
from scipy.linalg import lu
b=eval(input())
a=np.array(b)
P,L,U = lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: T. Gayathri
RegisterNumber: 212223100007
```
import numpy as np
from scipy.linalg import lu
a=eval(input())
c=eval(input())
b=np.array(a)
d=np.array(c)
P,L,U = lu(b)
x=np.linalg.solve(b,d)
print(x)
```

## Output:
## To find LU matrix
![image](https://github.com/gayumee/LU-Decomposition/assets/149037327/54ecca0f-ae0a-4e4d-8a31-46a01fc7231c)

## To solve LU matrix
![Screenshot 2024-05-08 202539](https://github.com/gayumee/LU-Decomposition/assets/149037327/fae50bfb-0658-4c50-aa6b-a99045e95e89)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

