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
# Register No:212225230264
# Developed By:SHREYAS M
# 1-Norm of a Matrix

import os
os.environ['OPENBLAS_NUM_THREADS']="1"
import numpy as np
a=np.array(eval(input()))
normal=np.linalg.norm(a,1)
print(normal)


# 2-Norm of a Matrix

import os
os.environ['OPENBLAS_NUM_THREADS']="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import os 
os.environ['OPENBLAS_NUM_THREADS']="1"
import numpy as np
a=np.array(eval(input()))
norminf=np.linalg.norm(a,np.inf)
print(f"{norminf:.2f}")



```
## Output:
### 1-Norm of a Matrix

<img width="1183" height="203" alt="image" src="https://github.com/user-attachments/assets/39839a23-a2ed-4712-a1a1-33598971ae49" />

### 2-Norm of a Matrix
<img width="1182" height="250" alt="image" src="https://github.com/user-attachments/assets/a1cb6985-b0ab-441b-8021-f645d60a0d8d" />


### Infinity Norm of a Matrix
<img width="1181" height="199" alt="image" src="https://github.com/user-attachments/assets/4966f483-a406-4a5a-9b2d-1309c8528a3a" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
