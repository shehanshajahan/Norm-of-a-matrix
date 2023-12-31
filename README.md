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
# Register No: 23008724
# Developed By: Shehan Shajahan
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np

# Type your code here

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-31 205331](https://github.com/shehanshajahan/Norm-of-a-matrix/assets/139317389/51182d82-1b5d-4d19-8a96-4dc28328828e)

### 2-Norm of a Matrix
![Screenshot 2023-12-31 205344](https://github.com/shehanshajahan/Norm-of-a-matrix/assets/139317389/b0b0be6a-da19-404f-88fa-44da71af1f28)

### Infinity Norm of a Matrix
![Screenshot 2023-12-31 205357](https://github.com/shehanshajahan/Norm-of-a-matrix/assets/139317389/49953c23-4f92-458f-8c2b-b10ab174c3c2)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
