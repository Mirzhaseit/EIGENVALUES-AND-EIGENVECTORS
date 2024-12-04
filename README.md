# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import NumPy
### Step 2: Define the Matrix
### Step 3: Compute Eigenvalues and Eigenvectors
### Step 4: print the result

## Program:
```
import numpy as np
a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))    
```






## Output:
![image](https://github.com/user-attachments/assets/4dc9f395-07e0-4a24-95c5-9e0e9570dd2c)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
