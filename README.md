# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

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
Developed by: MOHAN RAHUL S
RegisterNumber: 26018134
*/
```
import os 

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

from scipy.linalg import lu_factor,lu_solve

a=np.array(eval(input()))

b=np.array(eval(input()))

l,p=lu_factor(a)

x=lu_solve((l,p),b)

print(x)


## Output:
![lu decomposition]()
<img width="1228" height="795" alt="{32CAA318-0873-42B8-A03D-C6A06260A49E}" src="https://github.com/user-attachments/assets/2537eade-df89-4ba8-92d8-540cd1415c5f" />
<img width="1016" height="695" alt="{94964AB9-5A7A-4C80-A35E-A837A4939F33}" src="https://github.com/user-attachments/assets/e265122a-0657-4ce4-8581-e3d370e30576" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

