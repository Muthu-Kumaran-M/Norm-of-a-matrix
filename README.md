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
# Register No:23006606
# Developed By:Muthu Kumaran M
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix
![Exp 7 1](https://github.com/Muthu-Kumaran-M/Norm-of-a-matrix/assets/144979439/0a0905f3-333d-494f-b42c-16a224656424)


### 2-Norm of a Matrix
![Exp 7 3](https://github.com/Muthu-Kumaran-M/Norm-of-a-matrix/assets/144979439/d7ca657f-2497-4384-a3df-a1c964f6a8c3)


### Infinity Norm of a Matrix
![Exp 7 2](https://github.com/Muthu-Kumaran-M/Norm-of-a-matrix/assets/144979439/f56d99fb-1a9d-4ad2-9bc3-945bdb0a6908)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
