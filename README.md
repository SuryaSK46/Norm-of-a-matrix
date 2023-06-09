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
Developed by : Surya SK
Register Number : 212222100052
```
### 1-Norm of a Matrix
```
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
### 2-Norm of a Matrix
```
import numpy as np

# Type your code here

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
### Infinity Norm of a Matrix
```
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-06-10 025417](https://github.com/SuryaSK46/Norm-of-a-matrix/assets/127716537/29cce38b-e488-44c5-8ff4-d7cd71e51405)

### 2-Norm of a Matrix
![Screenshot 2023-06-10 025438](https://github.com/SuryaSK46/Norm-of-a-matrix/assets/127716537/6d4b5496-aefc-4824-9ed0-ba9d37cf453c)
### Infinity Norm of a Matrix
![Screenshot 2023-06-10 025515](https://github.com/SuryaSK46/Norm-of-a-matrix/assets/127716537/379bca48-e278-4864-a9f6-5c9adc88b7f0)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
