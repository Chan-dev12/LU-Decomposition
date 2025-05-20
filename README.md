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
```
/*
Program to find the L and U matrix.
Developed by: CHANTHRU V
RegisterNumber:212224240027
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: CHANTHRU V
RegisterNumber: 212224240027

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
piv,lu=lu_factor(a)
result=lu_solve((piv,lu),b)
print(result)
*/
```

## Output:

![image](https://github.com/user-attachments/assets/3dd9916c-8df7-459c-b635-9ac60c0e6abd)

![image](https://github.com/user-attachments/assets/0c6a2cd7-73de-4126-a2fc-681a99327a3f)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

