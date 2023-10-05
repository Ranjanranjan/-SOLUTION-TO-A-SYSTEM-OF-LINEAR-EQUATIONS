# SOLVING  SYSTEM  OF  LINEAR  EQUATION
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
```
#Program to find the solution for the given linear equations.
#Developed by: Ranjan K
#RegisterNumber:212222230116
import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
soln=np.linalg.solve(A,B)
print(soln)

```

## Output:
![Screenshot 2023-10-05 190045](https://github.com/Ranjanranjan/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/130027697/0c338f23-f92e-4ff1-bd17-c0ae923d75a9)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

