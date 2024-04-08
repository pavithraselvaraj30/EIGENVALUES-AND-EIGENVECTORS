# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: prepare the lists from each equations and gassign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Pavithra.S
#RegisterNumber:212223230147
import numpy as np
A=np.array([[2,2],[1,3]])
Eigenvalues,Eigenvectors=np.linalg.eig(A)
print("Eigen values are",Eigenvalues,"and Eigen Vectors are",Eigenvectors)
```

## Output:
![Screenshot 2024-04-08 141919](https://github.com/pavithraselvaraj30/EIGENVALUES-AND-EIGENVECTORS/assets/149366880/49e47db6-5f85-4ee1-a10c-25e6b36e5399)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
