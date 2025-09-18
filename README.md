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
# Register No: 212224230056
# Developed By: Dhanappriya s

# 1-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by:  Dhanappriya s
RegisterNumber: 212224230056
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
n="{:.2f}".format(ans)
print(n)


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by:  Dhanappriya s
RegisterNumber: 212224230056
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by:  Dhanappriya s
RegisterNumber: 212224230056
'''

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="1240" height="890" alt="Screenshot 2025-09-18 092251" src="https://github.com/user-attachments/assets/1cf6b16e-95e3-49a5-9eb6-53eb42cab972" />


### 2-Norm of a Matrix
<img width="1278" height="931" alt="Screenshot 2025-09-18 092312" src="https://github.com/user-attachments/assets/cca88f8f-166f-4673-be41-7080880e94a7" />


### Infinity Norm of a Matrix

<img width="1259" height="896" alt="Screenshot 2025-09-18 092332" src="https://github.com/user-attachments/assets/4d866c01-31b5-4ec6-83b3-5b053adfa16c" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
