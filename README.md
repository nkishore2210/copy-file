# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 

Step 1:

Create a 1.txt with some content in it

Step 2:

Open the 1.txt file in read mode

Step 3:

Create a copy.txt file using write mode

Step 4:

Copy the content of 1.txt file to copy.txt using write function

## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: N.Kishore
RegisterNumber: 212222240049

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:

![Screenshot 2023-06-04 141913](https://github.com/nkishore2210/copy-file/assets/118707090/c5589ec1-debb-4326-a39c-58b53b8081df)

![Screenshot 2023-06-04 141947](https://github.com/nkishore2210/copy-file/assets/118707090/196af631-2248-47a4-a551-61c1de201de8)

![Screenshot 2023-06-04 142002](https://github.com/nkishore2210/copy-file/assets/118707090/67cc2342-f8fc-496a-94c2-7a3cf85b81f5)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
