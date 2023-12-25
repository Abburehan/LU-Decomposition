# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import the numpy as np
2.from scipy.linalg import lu
3.enter the lists from each linear equationa and assgin in np.array()
4.using lu( )and store it in three variables
5.print the L and U matrix
6.end the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Abbu Rehan
RegisterNumber: 23010259
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
Program to find the LU Decomposition of a matrix.
Developed by: Abbu Rehan
RegisterNumber: 23010259
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot (150)](https://github.com/Abburehan/LU-Decomposition/assets/138849336/158dedd7-204e-4887-92dd-13d10539bda1)
![Screenshot (151)](https://github.com/Abburehan/LU-Decomposition/assets/138849336/0c51b38d-43fb-4877-9fc4-88b66fdffdde)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

