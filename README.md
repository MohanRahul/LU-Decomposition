# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the required libraries: numpy and lu from scipy.linalg.
2. Define the square matrix A using np.array().
3. Use lu(A) to decompose A into the permutation matrix P, the lower triangular matrix L and the upper triangular matrix U, so that A = P·L·U.
4. Print the matrices L and U (and P if needed).

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: mohan rahul s
RegisterNumber: 26018134
*/
```
import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: mohan rahuls 
RegisterNumber:26018134
*/
```
import numpy as np

from scipy.linalg import lu_factor,lu_solve

a=np.array(eval(input()))

b=np.array(eval(input()))

l,p=lu_factor(a)

x=lu_solve((l,p),b)

print(x)



## Output:
![lu decomposition]()
<img width="1184" height="825" alt="{F4D22049-8B1C-4C7E-8149-4D8B4B672D49}" src="https://github.com/user-attachments/assets/95150320-3884-4c2d-8721-5565a25968f3" />
<img width="1083" height="747" alt="{B36CB248-B009-482E-82C2-042AFEB84F6D}" src="https://github.com/user-attachments/assets/ec1f34a6-a272-4158-bb27-5a42b60e7056" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

