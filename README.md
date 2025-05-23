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
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm = np.linalg.norm(a,1)
print(norm)
# 2-Norm of a Matrix
import numpy as np
a = np.array(eval(input()))
norm = np.linalg.norm(a,2)
print(f"{norm:.2f}")
# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm = np.linalg.norm(a,np.inf)
print(f"{norm:.2f}")

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/8502fde4-0d3e-47fc-887a-f040f9608b7c)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/5022491b-dc59-41ee-90f7-64cebd33328d)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/ea50e08a-4758-4f71-b03e-e7533a37cf1a)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
