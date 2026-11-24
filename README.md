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
# Register No: 
# Developed By:
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))

```
## Output:
### 1-Norm of a Matrix
<br><img width="1327" height="823" alt="Screenshot 2026-11-19 222021" src="https://github.com/user-attachments/assets/25b69a5e-719f-4ba9-9318-d7ce0d63714f" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="1332" height="850" alt="Screenshot 2026-11-19 222037" src="https://github.com/user-attachments/assets/2ebc6979-4d21-4890-8796-148d56300d5a" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="1319" height="821" alt="Screenshot 2026-11-19 222058" src="https://github.com/user-attachments/assets/f0fe172e-10c1-4d3f-9cb0-1228d3905482" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
