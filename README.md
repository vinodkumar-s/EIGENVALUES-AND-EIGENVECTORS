# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import numpy which is needed.
### Step 2: 
Taking input by using ,np.array([]) from the user.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
finally,print the values of the eigen values and eigen vectors.

## Program:
 Program to find the eigen values and eigen vectors.
 
 Developed by: s.vinod kumar
 
 RegisterNumber:22004903
``` python
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

```

## Output:
![output](/output2.png)




## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
