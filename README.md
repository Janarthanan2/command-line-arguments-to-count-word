# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys

### Step 2:
open the file in read mood

### Step 3:
use the for loop

### Step 4:
use len function to count the number of words

### Step 5:
print the statement " word count in file = "

### Step 6:
run the programe to get the output

## PROGRAM:
```
'''
Program for getting the word count from the contents of a file using command line arguments
Developed by: JANARTHANAN V K
RegisterNumber: 212222230051
'''
import sys
count= 0
with open(sys.argv[0],'r') as f:
    for line in f:
        word=line.split()
        count+=len(word)
print("word count in file = ",count)

```
### OUTPUT:
![Screenshot 2023-06-10 133210](https://github.com/Janarthanan2/command-line-arguments-to-count-word/assets/119393515/ed624ddd-e314-42b2-b58e-650f61d74cf2)

![Screenshot 2023-06-10 133149](https://github.com/Janarthanan2/command-line-arguments-to-count-word/assets/119393515/1ef0fbb6-081a-42dc-8c08-22578f255922)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
