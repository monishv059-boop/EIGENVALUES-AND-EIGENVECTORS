# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library using import numpy as np.
### Step 2: Create the matrix using the np.array() function.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Store the eigenvalues and eigenvectors in variables and print the results.

## Program:
~~~
import numpy as np
a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))

~~~
## Output:
<img width="1237" height="222" alt="M EX 4 1" src="https://github.com/user-attachments/assets/acf6c8c6-62ea-4541-a150-7397cdc0fa79" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
