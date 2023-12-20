# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: importing numpy function.
### Step 2: assigning values to the variable in the list.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: use print function print the eigen values.

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: TH KARTHIK KRISHNA
#RegisterNumber: 23014165
import numpy as np
a=[[2,2],[1,3]]
b,c=np.linalg.eig(a)
print("Eigen values are",b,"and Eigen Vectors are",c)
~~~

## Output:

![Uploading image.png…]()

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
