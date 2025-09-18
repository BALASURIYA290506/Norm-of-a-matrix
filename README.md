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
# Register No: 212224240021
# Developed By: M BALASURIYA
# 1-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, np.inf)
print("%.2f"%(ans))



```
## Output:
### 1-Norm of a Matrix
<img width="769" height="953" alt="image" src="https://github.com/user-attachments/assets/6222fa92-db3b-4435-b32f-c311f9e1c032" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="741" height="943" alt="image" src="https://github.com/user-attachments/assets/49661526-02ff-474e-8324-8a09cdbe842a" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="731" height="918" alt="image" src="https://github.com/user-attachments/assets/2ec3ea65-1c1f-4435-939d-ca7c5dc17b60" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
