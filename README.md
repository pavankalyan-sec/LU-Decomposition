# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.  Import the numpy module to use the built-in functions for calculation
2.  Prepare the lists from each linear equations and assign in np.array()
3.  Using from scipy.linalg import lu and using from scipy.linalg import lu_factor,lu_solve to solve
4.  Prepare the lists from each linear equations and assign in np.array()

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Pavan Kalyan P
RegisterNumber: 212225240104
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Pavan Kalyan P
RegisterNumber: 212225240104
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:

<img width="1218" height="355" alt="image" src="https://github.com/user-attachments/assets/5a247354-125d-447f-a7e8-902d8d47bd86" />


<img width="1200" height="153" alt="image" src="https://github.com/user-attachments/assets/fa844648-b685-4be1-8236-953886a71c77" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

