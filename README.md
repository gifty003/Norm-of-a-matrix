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
# Register No: 22007928
# Developed By: Giftson Rajarathinam N
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)

# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)

# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)
```
## Output:

### 1-Norm of a Matrix
![image](https://github.com/gifty003/Norm-of-a-matrix/assets/145822352/a1c60536-8f44-496b-b35c-b2c680c1db67)


### 2-Norm of a Matrix
![image](https://github.com/gifty003/Norm-of-a-matrix/assets/145822352/2535f0fd-ee4e-4d61-9167-8f5f743b2bca)



### Infinity Norm of a Matrix
![image](https://github.com/gifty003/Norm-of-a-matrix/assets/145822352/ab9bd3fc-2a87-43a0-a033-d44f0e3a2364)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
