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
# Register No:24005882	
# Developed By:THARUN M
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
a="{:.2f}".format(ans)
print(a)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
a="{:.2f}".format(ans)
print(a)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/b8966f14-ff71-48b0-8945-c1c046399aec)

<br>
<br>
<br>

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/8cad4b1a-c9ce-4a79-906b-2411a9f39ded)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/229f9a3e-ff75-4f74-84cf-826efadaa13f)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
