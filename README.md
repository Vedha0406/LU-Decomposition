# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
# Step 1:
Define the package as scipy.linalg import lu.
# Step2:
Get input from the user and print L and U matrix using 'print'.
# Step 3:
Define a package as "from scipy.linalg import lu_factor,lu_solve" and create variable as 'X' include the package in that variable.
# Step 4:
print the variable 'X'. 

## Program:
(i) To find the L and U matrix:
```

'''Program to find L and U matrix using LU decomposition.
Developed by: GUGHAN S
RegisterNumber: 212223240043
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: VEDHASHREE G
RegisterNumber: 212223240171
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:

![Screenshot 2024-05-11 102905](https://github.com/Vedha0406/LU-Decomposition/assets/150884870/c4905fc3-422f-42ce-bb8d-8fbe55274bbc)

![EX5 SS](https://github.com/Vedha0406/LU-Decomposition/assets/150884870/1e5dcdd5-9ff3-49c6-86ef-fded9641ad42)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

