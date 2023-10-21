# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import thr numpy module to use the built-in functions for calculation 
### Step 2: 
Prepare the lists from each linear equations and assign in no.array()
### Step 3: 
Using the np.linalg.matrix_rank(),we can find the rank of the given matrix
### Step 4: 
End the program
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: kumarteja
#RegisterNumber:23003525
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inverse=np.linalg.inv(a)
print(inverse)
```
## Output:
![output](<Inverse of matrix.png>)
## Result:
Thus the inverse of given matrix is successfully solved using python program

