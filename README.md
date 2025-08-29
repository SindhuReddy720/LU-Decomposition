# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user
4. print result

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Pelleti Sindhu Sri
RegisterNumber:212224240113

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
Developed by: Pelleti Sindhu Sri
RegisterNumber: 212224240113

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
*/
```

## Output:

<img width="1423" height="960" alt="Screenshot 2025-08-29 232710" src="https://github.com/user-attachments/assets/63bf2a40-24e4-4dc6-bcec-68fde7a03b5a" />

<img width="1427" height="915" alt="Screenshot 2025-08-29 232829" src="https://github.com/user-attachments/assets/792a8962-af32-4809-9799-4911a052c54b" />

<img width="1402" height="963" alt="Screenshot 2025-08-29 232945" src="https://github.com/user-attachments/assets/f60ec82e-44f9-4323-a218-78afaeb20b2c" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

