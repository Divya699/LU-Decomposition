# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program
2.Import the necessary libraries(numpy,scipy.linalg)
3.Define the matrix using numpy
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program 
 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: DIVYA PRIYA.S
RegisterNumber: 25018016
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
Developed by:DIVYA PRIYA.S 
RegisterNumber: 25018016
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)


```

## Output:
<img width="1907" height="893" alt="Screenshot 2025-11-19 130813" src="https://github.com/user-attachments/assets/c52da122-4446-494a-bb0b-7d846382a7b7" />
<img width="1896" height="848" alt="Screenshot 2025-11-19 130837" src="https://github.com/user-attachments/assets/901c9900-4f7d-4de4-b7ee-28312d5a30b9" />
<img width="1545" height="819" alt="Screenshot 2025-11-19 130856" src="https://github.com/user-attachments/assets/b19b7dfe-4918-4552-92de-c49cc60bed2b" />
<img width="1416" height="433" alt="Screenshot 2025-11-19 130923" src="https://github.com/user-attachments/assets/50818664-0665-43a8-96c7-cad6b26dc965" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

