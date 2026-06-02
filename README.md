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
Python
# Register No:212225240049
# Developed By:Harshal Richu S
# 1-Norm of a Matrix
import os
os.environ ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="1300" height="251" alt="image" src="https://github.com/user-attachments/assets/0c7a367c-5d25-4784-bf0b-c99d5d825c8f" />


### 2-Norm of a Matrix
<img width="1383" height="282" alt="image" src="https://github.com/user-attachments/assets/19777ad2-d036-4e86-a537-d6ba990534ce" />


### Infinity Norm of a Matrix
<img width="1326" height="280" alt="image" src="https://github.com/user-attachments/assets/d5e23271-da74-4061-ab85-6bb309e17f30" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
