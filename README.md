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
# Register No: 212224230053
# Developed By: Deepak S

# 1-Norm of a Matrix

import numpy as np
A = np.array(eval(input()))
one_norm = np.linalg.norm(A, 1)
print(f"{one_norm:.2f}")

# 2-Norm of a Matrix

import numpy as np
A = np.array(eval(input()))
l2_norm = np.linalg.norm(A, 2)
print(f"{l2_norm:.2f}")

# Infinity Norm of a Matrix

import numpy as np
A = np.array(eval(input()))
inf_norm = np.linalg.norm(A, np.inf)
print(f"{inf_norm:.2f}")



```
## Output:
### 1-Norm of a Matrix
<img width="1261" height="917" alt="image" src="https://github.com/user-attachments/assets/faadd6b1-80a0-4271-adb3-49cf25e57802" />


### 2-Norm of a Matrix
<img width="1257" height="918" alt="image" src="https://github.com/user-attachments/assets/7918e8be-a902-4ce1-9407-43ad1d4c7e40" />


### Infinity Norm of a Matrix
<img width="1268" height="910" alt="image" src="https://github.com/user-attachments/assets/c0ded85e-e87e-40d8-9a01-34a26fca6d22" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
