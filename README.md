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
# Register No:V Vaishnavi
# Developed By:212224230294
# 1-Norm of a Matrix

import numpy as np 
matrix = eval(input())
arr = np.array(matrix)
norm1 = np.linalg.norm(arr,1)
print("{:.2f}".format(norm1))


# 2-Norm of a Matrix

import numpy as np
matrix = eval(input())
arr = np.array(matrix)
norm2 = np.linalg.norm(arr,2)
print("{:.2f}".format(norm2))




# Infinity Norm of a Matrix
import numpy as np
mat= np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix ="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix

<img width="1237" height="907" alt="m1" src="https://github.com/user-attachments/assets/cb9abb60-f1d8-4a40-b3f8-d5fc683ae7f8" />

### 2-Norm of a Matrix

<img width="1230" height="947" alt="m2" src="https://github.com/user-attachments/assets/cac63935-8beb-4c4f-b655-9755b3b880d4" />

### Infinity Norm of a Matrix

<img width="1226" height="892" alt="m3" src="https://github.com/user-attachments/assets/78f28f6e-d440-4966-abd2-b37745f68980" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
