# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
It imports the NumPy library and assigns it the alias np.
### Step 2: 
It creates a 3x3 matrix matrix using NumPy's array function:
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
It prints the calculated eigenvalues and eigenvectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Thamizh kumaran.S
#RegisterNumber: 23004070
import numpy as np
matrix = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigenvalues,eigenvectors=np.linalg.eig(matrix)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)
```

## Output:
![image](https://github.com/Thamizhjo/EIGENVALUES-AND-EIGENVECTORS/assets/123891476/3ebe5b27-82d0-4f8b-b62d-51679408f785)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
