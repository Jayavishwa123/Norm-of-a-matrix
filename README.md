# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Algorithm for 1-Norm of a Matrix:
1.Start the program.


2.Import the numpy library.


3.Read the matrix as input from the user.


4.Convert the input matrix into a NumPy array using np.array().


5.Use the function np.linalg.norm(arr, 1) to calculate the 1-norm of the matrix.


6.Display the result using print("{:.2f}".format(norm1)).


7.Stop the program.

## Algorithm for 2-Norm of a Matrix:
1.Start the program.


2.Import the numpy library.


3.Read the matrix as input from the user.


4.Convert the input matrix into a NumPy array using np.array().


5.Use the function np.linalg.norm(arr, 2) to calculate the 2-norm of the matrix.


6.Display the result using print("{:.2f}".format(norm2)).


7.Stop the program.

## Algorithm for Infinity Norm of a Matrix:
1.Start the program.


2.Import the numpy library.


3.Read the matrix as input from the user.


4.Convert the input matrix into a NumPy array using np.array().


5.Use the function np.linalg.norm(arr, np.inf) to calculate the infinity norm of the matrix.


6.Display the result using print("{:.2f}".format(norm_infinity)).


7.Stop the program.

## Program:
Python
# Register No: 212224230105
# Developed By:Jaya Vishwa S
# 1-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Jaya Vishwa S
RegisterNumber: 212224230105
'''

import numpy as np
matrix=eval(input())
arr=np.array(matrix)
norm1=np.linalg.norm(arr,1)
print("{:.2f}".format(norm1))
```


# 2-Norm of a Matrix



```
'''
Program to find 2-norm of a matrix.
Developed by: Jaya Vishwa S
RegisterNumber: 212224230105
'''
import numpy as np
matrix=eval(input())
arr=np.array(matrix)
norm2=np.linalg.norm(arr,2)
print("{:.2f}".format(norm2))
```


# Infinity Norm of a Matrix


```
'''
Program to find 2-norm of a matrix.
Developed by: Jaya Vishwa S
RegisterNumber: 212224230105
'''

import numpy as np
matrix=eval(input())
arr=np.array(matrix)
norm_infinity=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm_infinity))
```



## Output:
### 1-Norm of a Matrix
![alt text](<linalg 7(1).png>)
### 2-Norm of a Matrix
![alt text](<linalg 7(2).png>)

### Infinity Norm of a Matrix
![alt text](<linalg 7(3).png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
