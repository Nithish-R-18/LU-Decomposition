# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program.

2.Import the necessary libraries(numpy,scipy.linalg).

3.Define the matrix using numpy.

4.Use lu(),lu_solve(),lu_factor() to get the solutions.

5.End the program.

## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by: NITHISH R
RegisterNumber: 212225230202
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by: NITHISH R
RegisterNumber: 212225230202
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)

```

## Output:

(i)
<img width="1190" height="829" alt="maths ex 5 1" src="https://github.com/user-attachments/assets/3bf1af7e-1e7d-4b30-9fe8-ade38956f962" />


(ii)
<img width="1184" height="760" alt="maths ex5 2" src="https://github.com/user-attachments/assets/70aecb0d-953d-42b0-9d58-86e33dec2c0d" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

