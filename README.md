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
# Register No:212225230287
# Developed By:s.udhaya
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))





```
## Output:
### 1-Norm of a Matrix

<img width="672" height="223" alt="Screenshot 2026-02-25 143923" src="https://github.com/user-attachments/assets/f6db9545-140c-4569-bc8d-ff09a9bb4888" />


### 2-Norm of a Matrix


<img width="579" height="267" alt="Screenshot 2026-02-25 143938" src="https://github.com/user-attachments/assets/5b04ebef-fe32-415b-9679-b866c61581ab" />

### Infinity Norm of a Matrix


<img width="590" height="218" alt="Screenshot 2026-02-25 143946" src="https://github.com/user-attachments/assets/78b17dc3-5c1c-47b3-bed4-5b90a8dd5993" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
