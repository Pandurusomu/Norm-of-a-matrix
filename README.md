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
# Register No:  212223240111
# Developed By: Panduru somu
# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans  = np.linalg.norm(mat,1)
result = "{:.2f}".format(ans)
print(result)



# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
result = "{:.2f}".format(ans)
print(result)




# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
result = "{:.2f}".format(ans)
print(result)





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-30 170444](https://github.com/Pandurusomu/Norm-of-a-matrix/assets/148988619/3bff46d0-f12e-4ae0-aa71-7e54f24d12cf)

<br>
<br>
<br>

### 2-Norm of a Matrix
![Screenshot 2023-12-30 170502](https://github.com/Pandurusomu/Norm-of-a-matrix/assets/148988619/a72388f7-111f-425e-ab7a-20f4cd3f8d86)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![Screenshot 2023-12-30 170513](https://github.com/Pandurusomu/Norm-of-a-matrix/assets/148988619/affea205-93bc-4bca-9257-4f024e6a1549)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
