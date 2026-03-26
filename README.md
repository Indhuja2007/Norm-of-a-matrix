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
<img width="1262" height="615" alt="image" src="https://github.com/user-attachments/assets/fb8830c6-52bb-426f-8285-d02c18bbdeb5" />


### Infinity Norm of a Matrix
<img width="1269" height="585" alt="image" src="https://github.com/user-attachments/assets/edceb4b3-ff33-4e1a-996f-401add4af8a3" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
