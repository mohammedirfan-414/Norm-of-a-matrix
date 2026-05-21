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
# Register No:212225230179
# Developed By:H.MOHAMMED IRFAN
# 1-Norm of a Matrix
```

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
normal=np.linalg.norm(A,1)
print(normal)
```



# 2-Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")
```



# Infinity Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norminf=np.linalg.norm(A,np.inf)
print(f"{norminf:.2f}")
```




```
## Output:
### 1-Norm of a Matrix
![ex7/Screenshot 2026-05-21 111344.png](<Screenshot 2026-05-21 111344.png>)



### 2-Norm of a Matrix
![ex7/Screenshot 2026-05-21 111403.png>](<Screenshot 2026-05-21 111403.png>)



### Infinity Norm of a Matrix
![ex7/Screenshot 2026-05-21 111411.png](<Screenshot 2026-05-21 111411.png>)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
