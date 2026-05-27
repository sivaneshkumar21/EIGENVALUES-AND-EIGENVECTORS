# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program
## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by:SIVANESHKUMAR.N
#RegisterNumber: 25001283
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
~~~
## Output:
<img width="799" height="375" alt="{67150577-EE7F-4D88-87C0-AB14566EFBE5}" src="https://github.com/user-attachments/assets/b5fbbbaa-1b91-4777-b795-ee0bd08c569c" />

<img width="1366" height="250" alt="{F7C4BA37-309A-451D-ACB6-0DF5D5F85CB0}" src="https://github.com/user-attachments/assets/81f0bcbd-2634-46d7-9819-e5528a3555e9" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
