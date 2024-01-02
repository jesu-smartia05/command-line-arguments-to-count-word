# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import numpy as np

### Step 2: 
enter the input value

### Step 3: 
write a python program for getting the word count from the contents of a file using the command line arguments.

### Step 4:  
run the program

### Step 5: 
give the input

### Step 6: 
end te program

## PROGRAM:
```
# developed by: JESU SMARTIA A
# REG NO: 212223110016

import sys
count= 0
with open(sys.argv[1],'r') as file:
    for line in file:
        word=line.split()
        count+=len(word)
        
print("word count in file = ",count)

```
### OUTPUT:

![image](https://github.com/jesu-smartia05/command-line-arguments-to-count-word/assets/148514819/017ac9e4-3ff6-4009-8c4b-5f9746da4147)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
