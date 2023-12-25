# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```py
'''Program to find L and U matrix using LU decomposition.
Developed by: NAVEEN.S
RegisterNumber:23013059
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)


```
(ii) To find the LU Decomposition of a matrix
```py
'''Program to solve a matrix using LU decomposition.
Developed by:NAVEEN.S 
RegisterNumber:23013059 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

```

## Output:
![output](.![Alt text](image.png))
![output](.![Alt text](image-1.png))


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

