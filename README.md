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

# Register No:23006111
# Developed By:P.RAMYA
# 1-Norm of a Matrix
~~~
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
~~~




# 2-Norm of a Matrix
~~~
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
~~~




# Infinity Norm of a Matrix
~~~
import numpy as np
array1=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
~~~



## Output:
### 1-Norm of a Matrix

![image](https://github.com/23006111/Norm-of-a-matrix/assets/145981696/2c88baa7-2ee3-41c6-9f7a-c873274e95b1)


### 2-Norm of a Matrix

![image](https://github.com/23006111/Norm-of-a-matrix/assets/145981696/87b643a7-7b2d-4708-88d1-32fa37e12e90)


### Infinity Norm of a Matrix
![image](https://github.com/23006111/Norm-of-a-matrix/assets/145981696/39040009-bc12-4bd0-a6b7-2f4c1b0a4ca9)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
