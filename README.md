# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
import numpy as np       
A = np.array([[1,3],[2,5]])       
B = np.array([5,-3])   
X = np.linalg.solve(A,B)   
print(X)

## Output:
<img width="1556" height="803" alt="Screenshot 2025-11-19 104005" src="https://github.com/user-attachments/assets/ac6efe88-e94d-4d09-96e9-5e48f1baa3c0" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

