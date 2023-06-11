# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Open the file f1 in read mode.

### Step 2: Open the file f2 in append mode.
 
### Step 3: Copy the contents using write() with the for loop.

### Step 4: End the program.

## PROGRAM:
```
#Developed By: VASUNDRA SRI R
#Register No: 212222230168
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
 ```
            
### OUTPUT:
## program

![Screenshot 2023-06-11 101714](https://github.com/vasundrasriravi/copy-file/assets/119393983/7a4d3814-12d8-4810-80c6-5c4e16a1c56e)

## File 1

![Screenshot 2023-06-11 101740](https://github.com/vasundrasriravi/copy-file/assets/119393983/103caf5b-fa0f-4e46-82db-ae52ba720551)

## File 2

![Screenshot 2023-06-11 102627](https://github.com/vasundrasriravi/copy-file/assets/119393983/e773fdd3-b403-41b1-9756-13286f60ac12)

## File 1 copied into File 2

![Screenshot 2023-06-11 102657](https://github.com/vasundrasriravi/copy-file/assets/119393983/2017db26-fc8f-4d5c-9005-7aaadeddeade)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
