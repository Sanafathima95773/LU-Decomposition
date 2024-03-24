# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
(i)To find the L and U matrix
STEP 1:
Import the numpy module to use the built-in functions for calculation
STEP 2:
from scipy.linalg module import lu to find the L and U matrix
STEP 3:
get input from the user and apply lu function
STEP 4:
print L for L matrix and print U for U matrix
STEP 5:
End of program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Sana Fathima H
RegisterNumber: 212223240145
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Sana Fathima H 
RegisterNumber: 212223240145
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu=lu_factor(A)
x=lu_solve(lu,B)
print(x)
```

## Output:
![image](https://github.com/Sanafathima95773/LU-Decomposition/assets/147084627/f58d039d-fe94-4946-bfa6-b65d978927f1)


![Screenshot 2024-03-24 112157](https://github.com/Sanafathima95773/LU-Decomposition/assets/147084627/e87f98e0-a5a3-45bf-b114-ce717af9f994)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

