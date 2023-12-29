# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. using of numpy function
2. calling the function of a,b
3. using lu decomposition
4. print the  function

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: saranya s
RegisterNumber: 23013399
*/
# To print L and U matrix
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: saranya s
RegisterNumber: 23013399
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),b)
print(x)

*/
```

## Output:
![lu decomposition]()
(i) To find the L and U matrix

![image](https://github.com/srisrisaranya/LU-Decomposition/assets/148516638/7ffee9ff-f613-4011-9165-3343419d81af)
(ii) To find the LU Decomposition of a matrix
![image](https://github.com/srisrisaranya/LU-Decomposition/assets/148516638/bbaf8585-5731-43ae-84d4-59ad922addeb)






## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

