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
Developed by:someshvaran
RegisterNumber:25018410
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:someshvaran
RegisterNumber:25018410
import numpy as np
from scipy.linalg import lu_factor, lu_solve

A = np.array(eval(input("Enter matrix A: ")))
B = np.array(eval(input("Enter matrix B: ")))

lu, pivot = lu_factor(A)
x = lu_solve((lu, pivot), B)

print("Solution x =")
print(x) 

*/
```

## Output:
![lu decomposition]()!<img width="1718" height="576" alt="image" src="https://github.com/user-attachments/assets/1de9d1fb-b83f-46c5-823a-7dc97939adf3" />
<img width="1488" height="371" alt="image" src="https://github.com/user-attachments/assets/1083153e-2612-4b2b-8b16-3af20d0f8a04" />







## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

