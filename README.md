# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2:
 Prepare the list for each linear equation and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
```
Developed by:Mangari Deeraj 
RegisterNumber:212223100031
```
```
import numpy as np
g=np.array([[2,2],[1,3]])
h,i=np.linalg.eig(g)
print("Eigen values are {} and Eigen Vectors are {}".format(h,i))

```

## Output:
![image](https://github.com/user-attachments/assets/a43a856d-42e9-4d50-8afb-ba1f0b7107c4)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
