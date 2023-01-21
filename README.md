# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy and scipy from python library
2. Get input from user,using string concept
3. Calculate lu product and decomposition of the given matrices
4.Print the value of L
5.Print the value of U

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by:sivaram R 
RegisterNumber: 22008680
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U) 
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: sivaram R
RegisterNumber: 22008680
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:
(i)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

