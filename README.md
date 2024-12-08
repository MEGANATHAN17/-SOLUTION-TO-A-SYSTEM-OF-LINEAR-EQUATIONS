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
#Program to find the solution for the given linear equations.
#Developed by: MEGANATHAN R
#RegisterNumber:24900553
import numpy as np
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
B=np.array([-9,4,-1])
C=np.linalg.solve(A,B)
print(C)
```
## Output:
![Screenshot 2024-12-08 150624](https://github.com/user-attachments/assets/49b609b9-e0b9-43fb-9891-a56e211ac662)
![Screenshot 2024-12-08 150624](https://github.com/user-attachments/assets/852e518a-9651-4da2-b8ae-b5da343b42b2)




## Result: 
Thus the solutions for the linear equations are successfully solved using python program

