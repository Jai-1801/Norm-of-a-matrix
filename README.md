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

# to find the 1-Norm of a matrix 
# Register No: 23002572
# Developed By: Jai Surya

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# to find the 2-Norm of a matrix 
#Developed by: Jai Surya
#Register no: 23002572

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# to find the inf-Norm of a matrix 
#Developed by: Jai Surya
#Register no: 23002572

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![output01](/out%201.png)
### 2-Norm of a Matrix
![output02](/out%202.png)
### Infinity Norm of a Matrix
![output03](/out%203.png)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
