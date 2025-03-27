# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:

import numpy as np

def matrix_rank(matrix):
    arr = np.array(matrix)
    rank = np.linalg.matrix_rank(arr)
    return rank


matrix = [[3, 2, 5], [1, 1, 2], [3, 3, 6]]
rank = matrix_rank(matrix)
print(rank)
#Program to find the rank of a matrix.
#Developed by: Pugazh sozan.A
#RegisterNumber:212224240121


## Output:

![image](https://github.com/user-attachments/assets/8185b3d5-79e7-47c5-9d74-6b25abbeca23)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

