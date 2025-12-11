# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy as np
### Step 2: store the given array in a variable
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the Eigen values and eigen vectors of the given question

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: S.hariprasath
#Register Number: 25017723

import numpy as np

A = np.array([[2, 2], [1, 3]])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)


## Output:
<img width="1920" height="1200" alt="Screenshot 2025-12-11 144856" src="https://github.com/user-attachments/assets/e9b824e4-45f2-4ffe-8ca1-515dab12b22f" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
