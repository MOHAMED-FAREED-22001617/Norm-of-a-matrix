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
# 1-Norm of a Matrix
```Python
'''
Program to find 1-Norm of a matrix.
Developed by:MOHAMED FAREED.F
RegisterNumber:22001617
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


# 2-Norm of a Matrix
```python
'''
Program to find 2-norm of a matrix.
Developed by:MOHAMED FAREED.F
RegisterNumber:22001617
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```



# Infinity Norm of a Matrix
```python
'''
Program to find 2-norm of a matrix.
Developed by:MOHAMED FAREED.F
RegisterNumber:22001617
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>![Norm1](https://user-images.githubusercontent.com/121412904/214842186-2673fb19-867a-44e3-9494-615abef624bc.png)

<br>
<br>

### 2-Norm of a Matrix

<br>![Norm2](https://user-images.githubusercontent.com/121412904/214842740-44b8a489-2bc6-4107-8f13-c705e0c3cbae.png)

<br>
<br>

### Infinity Norm of a Matrix
<br>![Norm3](https://user-images.githubusercontent.com/121412904/214842281-13c88d59-04d7-43cb-9d8c-d9773f928b06.png)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
