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
# Register No:212222230182
# Developed By:YUVARAJ B
# 1-Norm of a Matrix
import numpy as np

mat= np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix ="{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
import numpy as np

mat= np.array(eval(input()))
ans= np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)






# Infinity Norm of a Matrix
import numpy as np 

mat =np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix ="{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Yuva2005raj/Norm-of-a-matrix/assets/118343998/55d17919-9c64-475f-a541-af5b3eca7845)


### 2-Norm of a Matrix
![image](https://github.com/Yuva2005raj/Norm-of-a-matrix/assets/118343998/8b52a474-7563-446b-bf2c-2f4c2446c8f5)


### Infinity Norm of a Matrix
![image](https://github.com/Yuva2005raj/Norm-of-a-matrix/assets/118343998/021b4567-d385-4edb-9d13-ae0a4cdb574e)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
