# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## 5(a)

### Step 1: Start and import the required libraries.

### Step 2: Get the input matrix from the user.

### Step 3: Perform LU decomposition to obtain P, L, and U matrices.

### Step 4: Display the lower triangular matrix (L) and upper triangular matrix (U), then stop.

## 5 (b)

### Step 1: Start and import the required Python libraries.

### Step 2: Get the coefficient matrix (A) and constant matrix (B) as input.

### Step 3: Perform LU factorization using `lu_factor()` and solve the equations using `lu_solve()`.

### Step 4: Display the solution matrix (X) and end of program

## Program:
(i) To find the L and U matrix
```
/*'''Program to find L and U matrix using LU decomposition.

Developed by: Niranjan p

RegisterNumber:26006895 

'''

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

from scipy.linalg import lu

a=eval(input())

P,L,U =lu(a)

print(L)

print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*

'''Program to solve a matrix using LU decomposition.

Developed by:NIRANJAN P 

RegisterNumber: 26006895
'''

# To print X matrix (solution to the equations)

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

from scipy.linalg import lu_factor,lu_solve

a=eval(input())

b=eval(input())

l,p=lu_factor(a)

x=lu_solve((l,p),b)

print(x)

*/
```

## Output:

## 5(a)

<img width="1045" height="722" alt="image" src="https://github.com/user-attachments/assets/fb51b653-a423-4c69-b170-2b0de305f4ee" />

<img width="1252" height="668" alt="image" src="https://github.com/user-attachments/assets/17659ae6-4ffb-43ce-9004-b234e8dafd65" />

## 5(b)

<img width="780" height="722" alt="image" src="https://github.com/user-attachments/assets/0c532f13-7c3b-43e5-880a-8af279b3b688" />

<img width="995" height="378" alt="image" src="https://github.com/user-attachments/assets/1268919b-be1a-4c42-b59a-28ef1bb47ec6" />






## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

