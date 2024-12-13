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
# Register No: 24900277
# Developed By: rizwan.b
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
inform="{:.2f}".format(ans)
print(inform)



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-13 100204](https://github.com/user-attachments/assets/5e9cfdb4-1765-4654-bd1a-5d256d85f6f5)


### 2-Norm of a Matrix
![Screenshot 2024-12-13 100212](https://github.com/user-attachments/assets/d8247957-d44e-4008-9977-44fcec6db721)


### Infinity Norm of a Matrix
![Screenshot 2024-12-13 100224](https://github.com/user-attachments/assets/eff9b2e5-82a4-4dbf-bc01-86e32befb760)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
