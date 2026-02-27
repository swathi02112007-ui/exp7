# Norm of a matrix

## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.

## Program:
~~~
```
Python
# Register No: 212225230279
# Developed By: Swathi P N

```

# 1-Norm of a Matrix

'''
Program to find 1-norm of a matrix.
Developed by: Swathi P N
RegisterName: 212225230279
'''

import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
result="{:.2f}".format(one_matrix)

print(result)

# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Swathi P N
RegisterNumber: 212225230279
'''
import numpy as np

# Type your code here
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
result="{:.2f}".format(two_matrix)

print(result)

# Infinity Norm of a Matrix

'''
Program to find infinity-norm of a matrix.
Developed by: Swathi P N
RegisterNumber: 212225230279
'''

import numpy as np

matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
result="{:.2f}".format(inf_matrix)

print(result)

~~~
## Output:

### 1-Norm of a Matrix

![alt text](<Exp 6.1-MA.png>)

### 2-Norm of a Matrix

![alt text](<Exp 6.2-MA.png>)

### Infinity Norm of a Matrix

![alt text](<Exp 6.3-MA.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
