# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
First we need to open the required file form which we need to copy the text.

## Step 2:
Using keyword "with" to open the requied file.

## Step 3:
Again using the with keyword to open the empty file.

## Step 4:
The empty file is open by using 'W' which is used to write only.

## Step 5:
The four function is used to take each line from the main file.

## Step 6:
write() is used to write the lines of main file to the empty file or to the directed file

## PROGRAM:
# Program  to copy contents from one file to another file
## DEVELOPED BY: OVIYA P
## REFERENCE NUMBER: 212223110033

def fun(f_one,f_second):
    with open(f_one) as fp:
        with open(f_second,"w") as fp1:
            data=fp.read()
            fp1.write(data)
f_one=input("enter the filename:1 ")
f_second=input("enter the filename:2 ")
fun(f_one,f_second)


### OUTPUT:
![image](https://github.com/Oviya24032K6/copy-file/assets/147139999/f624da7d-c0ea-42e6-8874-a9f5ffd7fceb)

![fileone](https://github.com/Oviya24032K6/copy-file/assets/147139999/2eff0d7d-c9cb-4652-a021-5d65c4f836ea)
![filesecond](https://github.com/Oviya24032K6/copy-file/assets/147139999/ded8510b-b96c-4306-aad6-72c9caab3f78)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
