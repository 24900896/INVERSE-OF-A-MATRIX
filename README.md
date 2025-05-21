# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Input Matrix A (square matrix).
### Step 2: Check: Compute the determinant of A.f it is zero, print that the matrix is non-invertible and stop.
### Step 3: Compute: If the determinant is non-zero, use np.linalg.inv(A) to compute the inverse.
### Step 4: Output: Print the inverse matrix.
## Program:
~~~
#Program to find the inverse of a matrix.
#Developed by: S.Sandeep
#RegisterNumber:212224230239

import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
solution=np.linalg.inv(A)
print(solution)
~~~
## Output:
![image](https://github.com/user-attachments/assets/c4beaab2-08aa-4f97-b0f1-72b002fe58f3)

## Result:
Thus the inverse of given matrix is successfully solved using python program

