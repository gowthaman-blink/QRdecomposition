# Algorithm for QR Decomposition
## Aim:
To implement QR decomposition algorithm using the Gram-Schmidt method.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Intialize the matrix Q and u
2.	The vector u and e is given by

    ![eqn1](./ex4.jpg)

    ![eqn2](./ex6.jpg)

    ![eqn3](./ex3.jpg)

3.	Obtain the Q matrix   
    ![eqn4](./ex1.jpg)
4.	Construct the upper triangular matrix R
    ![eqn5](./ex2.jpg)



## Program:
### Gram-Schmidt Method
```
program to qr decomposition using the gram-schemit method
developed by ak gowthaman
regester number :25017622
'''
import numpy as np
a=np.array(eval(input()))
q,r+np.linalg.qr(a)
print(q)
print(r)







```

## Output
```
<img width="1040" height="430" alt="image" src="https://github.com/user-attachments/assets/60fc38b2-ca6b-4f75-b67b-8025c301808c" />

```

## Result
Thus the QR decomposition algorithm using the Gram-Schmidt process is written and verified the result.
