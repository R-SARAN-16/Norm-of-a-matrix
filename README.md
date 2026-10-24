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
# Register No: 26004406
# Developed By: R SARAN
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(norm1)


# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,2)
print("{:.2f}".format(norm1))


# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,np.inf)
print("{:.2f}".format(norm1))



```
## Output:
### 1-Norm of a Matrix
<img width="1188" height="190" alt="image" src="https://github.com/user-attachments/assets/d92beae2-301e-4289-a8e9-26e5e4594a1f" />


### 2-Norm of a Matrix
<img width="1202" height="255" alt="image" src="https://github.com/user-attachments/assets/bfbf474a-232a-4cb9-aafc-d3290f6b06f9" />

### Infinity Norm of a Matrix
<img width="1187" height="202" alt="image" src="https://github.com/user-attachments/assets/50b2124d-45b5-46b6-a319-2c9af217a808" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
