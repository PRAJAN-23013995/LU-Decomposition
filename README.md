# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import lu(),lu_factor() and lu_solve() from scipy.linalg library
2. Use lu() method to find lower and upper matrix.
3.use lu_factor() and lu_solve to solve the two matrixes.
4.End the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: PRAJAN P
RegisterNumber: 212223240121
*/
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: PRAJAN P
RegisterNumber: 212223240121
*/
import numpy as np
import scipy.linalg as la
A=np.array(eval(input()))
B=np.array(eval(input()))
LU,piv=la.lu_factor(A)
x=la.lu_solve((LU,piv),B)
print(x)

```

## Output:
L AND U MATRIX:
![image](https://github.com/PRAJAN-23013995/LU-Decomposition/assets/150313345/c087781d-714a-409b-bf4c-4695c3b19d43)

LU DECOMPOSITION:
![image](https://github.com/PRAJAN-23013995/LU-Decomposition/assets/150313345/92bff19a-13e9-436c-87d3-9f71555f729f)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

