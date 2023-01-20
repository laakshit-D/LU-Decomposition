# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the list for a matrix and assign in np.array() 
### Step 3: 
Using the scipy.linalg, we can find the L and U matrix and LU decomposition of a matrix
### Step 4: 
End the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Laakshit D
RegisterNumber: 22000680
'''
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
p,l,u=lu(A)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Laakshit D
RegisterNumber: 22000680
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=eval(input())
res=lu_factor(a)
solution=lu_solve(res,b)
print(solution)
```

## Output:
(i)
![L and U](/Screenshot%20from%202023-01-20%2020-22-02.png)
(ii)

![lu decomposition](/Screenshot%20from%202023-01-20%2020-22-22.png)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

