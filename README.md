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
# Register No:22001030	
# Developed By:Subhikshaa M
# 1-Norm of a Matrix


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat, 1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat, 2)
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
![norm1](https://user-images.githubusercontent.com/118787344/214340750-6e3674fe-b5f4-4a3b-b590-5f00a0a7a113.png)



### 2-Norm of a Matrix

![norm2](https://user-images.githubusercontent.com/118787344/214340910-ecc47cef-72e8-46c7-b8e5-f2d1851989b6.png)


### Infinity Norm of a Matrix

![norm3](https://user-images.githubusercontent.com/118787344/214340969-b090ed12-6ad3-4acb-9e07-1dc341974821.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
