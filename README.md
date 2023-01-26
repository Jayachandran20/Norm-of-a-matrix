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
```Python program to find a Norm-of-a-matrix
# Register No:M.Jayachandran
# Developed By:22008847
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)





# 2-Norm of a Matrix:
# Developed By: Jayachandran
# Register No: 22008124
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
# Developed By: Jayachandran
# Register No: 22008124

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

## Output:

### 1-Norm of a Matrix
 
![1n](https://user-images.githubusercontent.com/118447015/214793611-d9df5440-d0ec-4be9-b5b6-b38e894ebfb0.png)

 
### 2-Norm of a Matrix

![2n](https://user-images.githubusercontent.com/118447015/214793755-4334c028-af40-4924-9389-773a56be0862.png)


### Infinity Norm of a Matrix
![3n](https://user-images.githubusercontent.com/118447015/214793838-6747dbd6-b56d-41fc-b6da-d83145261e36.png)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
