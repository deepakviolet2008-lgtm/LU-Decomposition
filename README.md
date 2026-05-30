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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)

```

## Output:
<img width="1239" height="492" alt="image" src="https://github.com/user-attachments/assets/ac9387a4-4a32-471c-9c7e-d57efdc8c54d" />
<img width="1231" height="226" alt="image" src="https://github.com/user-attachments/assets/52127a5a-8f1d-4899-a3d6-55c2337a5bea" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

