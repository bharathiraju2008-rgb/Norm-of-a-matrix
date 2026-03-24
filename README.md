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
# Register No:212225230032
# Developed By:R.Bharathi Shankar
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
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<img width="650" height="774" alt="Screenshot 2026-03-24 184839" src="https://github.com/user-attachments/assets/ffcdac75-b16e-411e-a6b1-e548c7b171e7" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="664" height="808" alt="Screenshot 2026-03-24 184855" src="https://github.com/user-attachments/assets/1dff144f-788c-43ea-a886-66b71829d745" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="602" height="765" alt="Screenshot 2026-03-24 184908" src="https://github.com/user-attachments/assets/b36dc3ee-29d7-41e8-bbd0-3b0895bf7d54" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
