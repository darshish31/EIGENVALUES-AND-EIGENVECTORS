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
#Program to find the eigen values and eigen vectors.
#Developed by:Darshini B 
#RegisterNumber:24008783

import numpy as np
matrix = np.array([[-2, 2, -3], [2, 1, -6], [-1, -2, 0]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")

```

## Output:
![image](https://github.com/user-attachments/assets/df227fcd-a264-44fc-96b3-7b2c3ebe1ff8)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
