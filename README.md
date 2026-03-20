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
# Register No: 212225040203
# Developed By: LOGESH R
# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(f"{norm1:.2f}")


# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")




# Infinity Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
res=np.linalg.norm(A,np.inf)
print(f"{res:.2f}")




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1137" height="536" alt="image" src="https://github.com/user-attachments/assets/0bd2314e-5229-4565-9330-deb971f08349" />
<img width="744" height="349" alt="image" src="https://github.com/user-attachments/assets/b02e1367-f9e5-4da5-ab23-f63c9ef0c4f2" />




### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1127" height="691" alt="image" src="https://github.com/user-attachments/assets/e0da5a55-71f6-4502-be37-5d962a7a9a2b" />
<img width="734" height="388" alt="image" src="https://github.com/user-attachments/assets/fc11a2d7-7ee9-4f9b-aa9e-c9c3fb250fc1" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1115" height="557" alt="image" src="https://github.com/user-attachments/assets/fb56f856-0af5-4335-957e-203ab362d5ed" />
<img width="888" height="345" alt="image" src="https://github.com/user-attachments/assets/e5e5eae6-de89-43aa-aa72-183dab8d8c00" />




## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
