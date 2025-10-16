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
# Register No:212224110052
# Developed By: S.D. Surendar
# 1-Norm of a Matrix
# Register No:212224110052
# Developed By: S.D. Surendar
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix="{:2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname : S.D. Surendar
RegisterNumber: 212224110052
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix ="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: S.D. Surendar
RegisterNumber: 212224110052
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
<img width="821" height="772" alt="image" src="https://github.com/user-attachments/assets/568cf7e5-ea0d-4ee8-b118-b41ba75a4748" />


### 2-Norm of a Matrix
<img width="1315" height="795" alt="Screenshot 2025-10-16 110738" src="https://github.com/user-attachments/assets/f1fa2a70-6297-46b2-a380-57e64aa12cec" />



### Infinity Norm of a Matrix
<img width="821" height="772" alt="Screenshot 2025-10-16 082438" src="https://github.com/user-attachments/assets/74ae181d-5034-47e2-b39a-5efbec387a8a" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
