# Word-count
### Name: Anbuselvan.S
### Reference No: 23005959
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open a exsiting text file

### Step 2:
Read the file and store in the variable

### Step 3:
count=0

### Step 4:
using for loop split the word

### Step 5:
using count+=1

### Step 6:
print the count

### Step 7:
End the program

## PROGRAM:
```
To write a python program for getting the word count from a text.
Developed by: Anbuselvan.S
Reference no: 23005959

with open("myfile.txt","r") as file:
    line=file.read()
    count=0
    for i in line.split():
        count+=1
    print(count)
```
### OUTPUT:
![image](https://github.com/anbuselvan1519/Word-count/assets/139841744/bc30848d-b4e6-43d5-b83b-d63594ab9f32)
### TEXT FILE
![image](https://github.com/anbuselvan1519/Word-count/assets/139841744/746722ce-36fd-4aae-b2f7-25669fdc95ef)

## RESULT:
Thus the program is written to find the word count from a text.
