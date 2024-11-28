# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Define or input the square matrix for which eigenvalues and eigenvectors are to be calculated. 
### Step 2: Use the numpy library for efficient numerical computations.
### Step 3: Apply numpy.linalg.eig() to the matrix.
### Step 4: Print or return the computed eigenvalues and eigenvectors.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by:Darshini B
#RegisterNumber:24008783

import numpy as np
matrix = np.array([[1, 0, 3], [-1,2,-2], [2,3,-1]])
try:
    inverse = np.linalg.inv(matrix)
    print(inverse)
except np.linalg.LinAlgError:
    print()

```

## Output:
![image](https://github.com/user-attachments/assets/d700368d-8a84-4f83-a5d7-c15f745051b3)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
