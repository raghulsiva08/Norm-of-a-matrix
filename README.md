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
# Register No:Raghul.s
# Developed By:212225040325
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



```
## Output:
### 1-Norm of a Matrix
<img width="1329" height="272" alt="image" src="https://github.com/user-attachments/assets/65be1997-84c3-455c-884b-3fd67cfaf34a" />


### 2-Norm of a Matrix
<img width="1558" height="489" alt="image" src="https://github.com/user-attachments/assets/5b80b6e9-3328-4f23-8ffa-034df62ab1d3" />

### Infinity Norm of a Matrix
<img width="1286" height="236" alt="image" src="https://github.com/user-attachments/assets/ed121274-a366-4ca5-8596-8a44633609c1" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
