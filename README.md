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
```Python
# Register No: S.DIVYA DHARSHINI
# Developed By: 24900891
# 1-Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,1)
n="{:.2f}".format(a)
print(n)

# 2-Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
n="{:.2f}".format(a)
print(n)

# Infinity Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
n="{:.2f}".format(a)
print(n)

```
## Output:
### 1-Norm of a Matrix
![alt text](exp.no.07-1.png)


### 2-Norm of a Matrix
![alt text](exp.no.07-2.png)


### Infinity Norm of a Matrix
![alt text](exp.07-3.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
