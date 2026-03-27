# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

STEP 1: Initialize Inputs: Read the given square matrix A and the constant vector B.

STEP 2: Decompose Matrix: Factorize matrix A into a lower triangular matrix (L) and an upper triangular matrix (U) so that A = L * U.

STEP 3: forward Substitution: Solve the equation L * Y = B to find the temporary vector Y.

STEP 4: Backward Substitution: Using that vector Y, solve the equation U * X = Y to find your final solution vector X. Print the result.

## Program:
```
'''Program to find the L and U matrix.
Developed by: MOHAMMED HANEEF M
RegisterNumber: 212225040249 '''

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```


## Output:


<img width="1151" height="340" alt="image" src="https://github.com/user-attachments/assets/e557f067-fbbf-4d70-8240-548a9316687e" />

<img width="1428" height="471" alt="image" src="https://github.com/user-attachments/assets/e9a92931-3090-4a17-8086-4cf363d93fe4" />

<img width="1246" height="243" alt="image" src="https://github.com/user-attachments/assets/d6763b73-cfad-44f8-9f23-22c5c43a93c7" />

<img width="1413" height="440" alt="image" src="https://github.com/user-attachments/assets/c0aad126-74df-4bfc-9012-d606e6b6507c" />





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

