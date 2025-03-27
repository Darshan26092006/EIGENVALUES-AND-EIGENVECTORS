# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
import numpy as np

# Define the matrix
matrix = np.array([[2, 2], 
                   [1, 3]])

# Compute eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(matrix)

# Display the results
print("Eigen values are", eigenvalues,"and Eigen Vectors are", eigenvectors)


## Output:
![Screenshot 2025-03-27 203659](https://github.com/user-attachments/assets/6e292892-f6bc-4a22-8680-92f1a4d8bd2f)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
