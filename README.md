# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

Step 1:
Import sys.

Step 2:
Assign a variable count =0.

Step 3:
Open a file in read mode.

Step 4:
Iterate a variable(lines) through the file.

Step 5:
Assign a variable words = lines.split().

Step 6:
Now iterate through the variable and increase the count: and print the count value

## PROGRAM:

#Developed By:- M.HARI KRISHNA
#Reference number:-21002044

import sys
count =0
with open(sys.argv[1],'r') as f:
    for lines in f:
        words = lines.split()
        count+=len(words)
print("Number of words in a file:",count)  

### OUTPUT:

<img width="523" alt="mekkini 3" src="https://user-images.githubusercontent.com/94882905/154802374-9bbb287e-c083-42aa-a443-d4a33334b9b1.png">
<img width="746" alt="mekkini4" src="https://user-images.githubusercontent.com/94882905/154802385-d2dfe373-3e1f-4444-bf63-55a75f5f2ff2.png">




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
