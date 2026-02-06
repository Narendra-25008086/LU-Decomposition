# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2. Import the NumPy library and define the given square matrix.
3. Perform LU Decomposition to obtain the Lower triangular matrix L and Upper triangular matrix U.
4.Display matrices L and U and stop the program. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: NARENDRA KRISHNAN KS
RegisterNumber: 212225240096
*/

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the L and U matrix.
Developed by: NARENDRA KRISHNAN KS
RegisterNumber: 212225240096
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
<img width="1382" height="515" alt="image" src="https://github.com/user-attachments/assets/2a550217-d9cc-4851-8f3b-b5467cee04d4" />

<img width="1338" height="203" alt="image" src="https://github.com/user-attachments/assets/2ada267a-f029-4cb3-8954-b0fed1c9b845" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

