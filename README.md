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
# Register No:212223230095
# Developed By: Kamesh.R

### Program:for 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


### Program for  2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```



### Program for Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-01 150418](https://github.com/23002027/Norm-of-a-matrix/assets/139752981/786f0382-4aa5-4ad2-ba68-31d68bbad005)
### 2-Norm of a Matrix
![Screenshot 2024-05-01 150432](https://github.com/23002027/Norm-of-a-matrix/assets/139752981/a37e0051-9919-4b9b-bd54-d3b96deb07c0)
### Infinity Norm of a Matrix
![Screenshot 2024-05-01 150446](https://github.com/23002027/Norm-of-a-matrix/assets/139752981/e99487a2-5e62-46aa-a33e-0842f26a019d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
