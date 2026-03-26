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
```
# Register No: 212225040133
# Developed By: INDHUJA.K
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,1):.2f}")


# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,2):.2f}")



# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,np.inf):.2f}")
```
## Output:
### 1-Norm of a Matrix
<img width="343" height="112" alt="image" src="https://github.com/user-attachments/assets/41796411-7720-4542-aab9-36ce46e46df5" />


### 2-Norm of a Matrix
<img width="307" height="126" alt="image" src="https://github.com/user-attachments/assets/ccc8a7c4-4a22-4f91-9add-a899e353d4a0" />


### Infinity Norm of a Matrix
<img width="315" height="90" alt="image" src="https://github.com/user-attachments/assets/5bf3d7e2-c193-460d-83e7-1be4f8681e52" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
