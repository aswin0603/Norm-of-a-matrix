# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 1-norm of the matrix using np.linalg.norm(variable, 1)
3. Find the 2-norm of the matrix using np.linalg.norm(variable, 2)
4. Find the infinity-norm of the matrix using np.linalg.norm(variable, np.inf)
5. Print the norm of the matrix in two decimal places and end the program.


## Program:
```Python

# Register No: 24900642
# Developed By: Aswin B

# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print (norm_of_matrix)


# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print (norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print (norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Record 07-01](https://github.com/user-attachments/assets/10e35780-db74-4188-a258-1e34cae2a136)


### 2-Norm of a Matrix
![Record 07-02](https://github.com/user-attachments/assets/04de6069-bb8e-4b81-b866-d0da0bc0e009)


### Infinity Norm of a Matrix
![Record 07-03](https://github.com/user-attachments/assets/6a50f9a9-5407-4d7d-8faa-38f1a94d38bc)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
