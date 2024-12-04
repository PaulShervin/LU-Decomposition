# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.find the l and u matirx by using numpy and linalg from scipy
2.print the l matrix and u matirx
3.find the lu decomposition by using numpy and lu_factor and lu_solve
4.print the the following matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
```
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)

## Output:
![lu decomposition]()![Screenshot 2024-11-17 165917](https://github.com/user-attachments/assets/2bae303e-0559-492a-9b30-e7b296dcdd3b)
![Screenshot 2024-11-17 165903](https://github.com/user-attachments/assets/92d04267-308e-486a-b029-a02d40da32e5)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

