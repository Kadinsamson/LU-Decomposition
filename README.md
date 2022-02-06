# LU Decomposition without zero on the diagonal

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
5.


## Program:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:KADIN SAMSON L 
RegisterNumber: 21001514
*/
from scipy.linalg import lu 
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)
```

## Output:
![github logo](decomposition1.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.


# LU Decomposition without zero on the diagonal

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
5.


## Program:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:KADIN SAMSON L 
RegisterNumber: 21001514
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,plv=lu_factor(a)
x=lu_solve((lu,plv),b)
print(x)
```

## Output:
![github logo](decomposition2.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

