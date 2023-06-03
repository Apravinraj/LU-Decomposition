# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
 step 1: Import numpy library using import statement.

 Step 2: From scipy package import lu().

 Step 3: Get input from user and pass it as an array.

 Step 4: Get P, L, U matrix using lu()

 Step 5: Print L and U matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Pravin raj.A
RegisterNumber:212222240079 
*/
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Pravin raj.A
RegisterNumber: 212222240079
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3,2,7],[2,3,1],[3,4,1]])
B=np.array([4,5,7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
```

## Output:
#  LU Decomposition to find L and U matrix.
![Screenshot 2023-06-03 094456](https://github.com/Apravinraj/LU-Decomposition/assets/118707879/5dc797c9-a193-4b9e-8475-f63009f7c040)

#  LU Decomposition to solve a matrix.
![Screenshot 2023-06-03 094528](https://github.com/Apravinraj/LU-Decomposition/assets/118707879/31492da8-5c44-4915-b4e9-46f6f34c0c1b)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

