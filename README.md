# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2:
Read the file and store in a variable.

### Step 3:
Now create a new file in which we want to paste the content using write access mode.

### Step 4:
Use write function to copy the read file that has been stored in the variable.

### Step 5:
The content in the original file will be copied in the new file.

### Step 6:
End the program.

## PROGRAM:
'''
Developed by: RAJKUMAR
RegisterNumber: 212223230166
'''
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
### OUTPUT:
![293595536-549d93d9-b001-4e88-b26d-0d20f8bc6801](https://github.com/Rajkumar28072005/copy-file/assets/144980101/3191e51c-287d-4089-b225-f07b0d50ff82)

![293595519-b8abe3a9-3476-4b1a-a89a-fb648c9dbed0](https://github.com/Rajkumar28072005/copy-file/assets/144980101/cb9cb874-3e6d-4eb1-8f00-5cfacc8af0ef)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
