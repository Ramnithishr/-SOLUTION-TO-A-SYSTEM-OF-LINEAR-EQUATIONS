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
```

import numpy as np
A=[[1,3],[2,5]]
B=np.array([5,-3])
C=np.linalg.solve(A,B)
print(C)

```
## Output:
![Screenshot 2024-11-27 094416](https://github.com/user-attachments/assets/99c4079d-fa24-4e1b-926c-976d2e8bd7ac)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

