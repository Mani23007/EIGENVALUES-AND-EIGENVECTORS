# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors.
## Equipment’s required:
1. 	Hardware – PCs.
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner.
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each linear equations and assign in np.array().
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: MANIKANDAN K
#RegisterNumber: 212224230150

import numpy as np
A=np.array([[2,2],[1,3]])
val,vec=np.linalg.eig(A)
print(f"Eigen values are {val} and Eigen Vectors are {vec}")
~~~


## Output:
<img width="1288" height="785" alt="image" src="https://github.com/user-attachments/assets/bbe739e4-4300-440a-8105-238ef4cbcbc8" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
