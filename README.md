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
# Register No:VISHAL M
# Developed By:212225240186
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a=np.array(eval(input()))
print(f"{np.linalg.norm(a,1):.2f}")





# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a=np.array(eval(input()))
print(f"{np.linalg.norm(a,2):.2f}")


# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a=np.array(eval(input()))
print(f"{np.linalg.norm(a,np.inf):.2f}")






# 2-Norm of a Matrix




# Infinity Norm of a Matrix





```
## Output:
### 1-Norm of a Matrix
<img width="1329" height="272" alt="image" src="https://github.com/user-attachments/assets/a52824e3-941a-4d0b-8e79-a8d18f521def" />

### 2-Norm of a Matrix
<img width="1558" height="489" alt="image" src="https://github.com/user-attachments/assets/a2877669-5547-49ce-bafd-b744e2035fe0" />


### Infinity Norm of a Matrix
<img width="1286" height="236" alt="image" src="https://github.com/user-attachments/assets/c96dfd13-319d-43ee-8113-eacba61c1791" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
