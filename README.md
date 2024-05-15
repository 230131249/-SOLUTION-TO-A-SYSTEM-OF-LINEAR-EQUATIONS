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
#Program to find the solution for the given linear equations.
#Developed by: JAYASURIYA J
#RegisterNumber:212223230088
import numpy as np

# Define the coefficient matrix A
A = np.array([[1, 3],
              [2, 5]])

# Define the constant matrix B
B = np.array([5, -3])

# Solve the system of equations
solution = np.linalg.solve(A, B)

# Print the solution in the desired format
print(solution)

## Output:
![image](https://github.com/230131249/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/150232701/c81a1a72-fb13-4175-ad81-64ba98779996)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

