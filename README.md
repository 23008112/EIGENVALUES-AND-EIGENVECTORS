# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the list from the given two dimension matrix and assign in np.array()
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the result
### Step 5:
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: R.Sanjana
#RegisterNumber: 23008112

import numpy as np
a=[[2,-3,0],[2,-5,0],[0,0,3]]
values,vectors=np.linalg.eig(a)

print("Eigen values are",values,"and Eigen Vectors are",vectors)

```
## Output:
![Screenshot 2023-12-23 114940](https://github.com/23008112/EIGENVALUES-AND-EIGENVECTORS/assets/138972470/8b891f97-1fa5-4c64-92d0-e805e76046c6)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
