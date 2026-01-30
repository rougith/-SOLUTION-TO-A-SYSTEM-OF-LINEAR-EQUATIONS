# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
##Developed By: Rougith D
##Register Number: 25017014
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
import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
C=np.linalg.solve(A,B)
print(C)
```
## Output:
<img width="1020" height="680" alt="{8A9F1DCC-1D29-4037-8196-9B58E8F57A85}" src="https://github.com/user-attachments/assets/93315dec-050f-49f7-a24c-ec4b4d6af285" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

