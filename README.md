# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the Changes

## Program:
~~~
#Program to find the inverse of a matrix.
#Developed by: Sai Darshan
#RegisterNumber:21003195
import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
Solution=np.linalg.inv(A)
print(Solution)
~~~
## Output:
![GitHub Logo](inverse.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

