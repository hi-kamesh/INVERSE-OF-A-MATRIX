# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy
### Step 2: use np.linalg
### Step 3: proceed with if else statement
### Step 4: end the code

## Program:


import numpy as np

# Given matrix
A = np.array([[2, 1, 1], [1, 1, 1], [1, -1, 2]])

# Check if the matrix is invertible (determinant is not zero)
det = np.linalg.det(A)

if det != 0:
    # Find the inverse of the matrix
    A_inv = np.linalg.inv(A)
    print(A_inv)
else:
    print("The matrix is singular and cannot be inverted.")










## Output:
![Screenshot 2024-12-03 100508](https://github.com/user-attachments/assets/d1b24f40-f378-4147-9a8c-dbbd30dc5bb2)


## Result:
Thus the inverse of given matrix is successfully solved using python program

