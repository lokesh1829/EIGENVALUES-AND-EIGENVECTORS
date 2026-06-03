# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

## Step1 :
Import the numpy module to use the built-in functions for calculation

## Step 2:
Prepare the lists from each linear equations and assign in np.array()

## Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

## Step 4:
End the program
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```

## Output:
<img width="1331" height="780" alt="image" src="https://github.com/user-attachments/assets/257d0280-5965-4a51-a6e3-7e32cb8b1ee8" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
