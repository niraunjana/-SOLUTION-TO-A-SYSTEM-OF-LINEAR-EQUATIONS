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
```python
#Program to find the solution for the given linear equations.
#Developed by: NIRAUNJANA GAYATHRI G R
#RegisterNumber: 22008369
import numpy as np
A = np.array([[1,3],[2,5]])
B = np.array([5,-3])
sol = np.linalg.solve(A,B)
print(sol)
```

## Output:
![WhatsApp Image 2023-01-22 at 16 56 29](https://user-images.githubusercontent.com/119395610/213913358-a5468094-5722-4e79-aad1-45b18f3030e1.jpg)
![WhatsApp Image 2023-01-22 at 16 56 38](https://user-images.githubusercontent.com/119395610/213913366-4d206c4d-23a1-4225-acbc-536782e476c6.jpg)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

