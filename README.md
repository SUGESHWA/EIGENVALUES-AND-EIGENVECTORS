# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 : Import the numpy module to use the built-in functions for calculation
## Step 2: Prepare the lists from each linear equations and assign in np.array()
## Step 3: Using the np.linalg.solve(), we can find the solutions.
## Step 4: End the program

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: S.Sugeshwa
#RegisterNumber:24900706
import numpy as np
A = np.array([[4,2],[2,4]])
eigenvalues, eigenvectors = np.linalg.eig(A)

print(f"Eigen values are {np.round(eigenvalues, 1)} and Eigen Vectors are {np.round(eigenvectors, 8)}")
~~~
## Output:
![image](https://github.com/user-attachments/assets/5ae8e911-e12e-4b1c-a2dc-7391cf60ec94)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
