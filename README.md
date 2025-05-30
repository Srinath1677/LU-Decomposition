# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import numpy library using import statement   
2.From scipy package import lu()  
3.Get input from user and pass it as an array  
4.Get P,L,U matric using lu()   
5.Print L and U matrix  

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Srinath YG
RegisterNumber: 212224230274
*/
```
```python
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
## Algorithm 

1. Take input for matrix `A` and vector `b` as NumPy arrays.
2. Perform LU decomposition on `A` using `lu_factor()`.
3. Solve the linear system using `lu_solve()` with the LU factors and `b`.
4. Print the solution vector `X`.
5. End the program.

```
/*
Program to find the LU Decomposition of a matrix.
Developed by:Srinath YG 
RegisterNumber: 212224230274
*/
```
```python
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:

![image](https://github.com/user-attachments/assets/252fa370-82c7-4c78-8f84-aa021783cb82)

![image](https://github.com/user-attachments/assets/f7db5a36-322f-43c1-a3cd-e4b7ba0663fb)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

