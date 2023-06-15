# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file f1 in read mode.

### Step 2: 
Open the file f2 in append mode.
 
### Step 3: 
Copy the contents using write() with the for loop.

### Step 4:  
End the program.

## PROGRAM:
```
#Developed by:LATHISH KANNA .M
#Reg no:212222230073

with open('f1.txt','r')as f1:
    with open('f2.txt','a')as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![image](https://github.com/divyakumars/copy-file/assets/119393621/e7617f11-006d-4e19-a381-34a69a202e37)

### FILE 1:
![image](https://github.com/divyakumars/copy-file/assets/119393621/fac0dbf8-fc0c-42dd-b975-24db5ca10e5f)

### FILE 2:
![image](https://github.com/divyakumars/copy-file/assets/119393621/c5f30a2f-d58b-431c-a3ad-712488016e1c)

### FILE 1 copied to FILE 2

![image](https://github.com/divyakumars/copy-file/assets/119393621/001b6ef9-57fa-4e02-94fa-3fee619298f3)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
