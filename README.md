# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.STEP 1: Import the numpy module to use the built-in functions for calculation 
2.STEP 2:Prepare the lists from each linear equations and assign in np.array()
3.STEP 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix. 
4.STEP 4:End the program


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SATHISH KUMAR.T
RegisterNumber:212224100053 
*/
```
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
Developed by:SATHISH KUMAR.T 
RegisterNumber:21222410053 
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
pv,lu=lu_factor(A)
result=lu_solve((pv,lu),B)
print(result)
```

## Output:
![lu decomposition](<Screenshot 2025-04-11 204213.png>)
![lu decomposition](<Screenshot 2025-04-11 202627.png>)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

