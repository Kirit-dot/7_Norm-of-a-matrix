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
# Register No: KIRIT LULLA
# Developed By: 212225230139
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,1)
norm="{:.2f}".format(a)
print(norm)


# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
norm="{:.2f}".format(a)
print(norm)


# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
ma=np.array(eval(input()))
a=np.linalg.norm(ma,np.inf)
norm="{:.2f}".format(a)
print(norm)


```
## Output:
### 1-Norm of a Matrix
<img width="561" height="193" alt="image" src="https://github.com/user-attachments/assets/6a80003e-7519-43ca-8481-44d8e4058d86" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="526" height="258" alt="image" src="https://github.com/user-attachments/assets/3d025cc8-cc3d-4590-ac3f-5c443b2df8d1" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="548" height="207" alt="image" src="https://github.com/user-attachments/assets/b62db872-e19c-4446-b4c3-6503603b51a9" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
