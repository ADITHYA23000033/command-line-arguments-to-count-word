# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys
### Step 2: 
Initially make count = 0 
### Step 3: 
Open the content file using command line arguments.
### Step 4:  
By using for loop name the function as "line"
### Step 5: 
Split the line using .split
### Step 6: 
Split the line using .split 
## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: Aditya V
RegisterNumber: 23000033
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:
![5 B](https://github.com/ADITHYA23000033/command-line-arguments-to-count-word/assets/148514544/c76317dd-c2d4-4915-afe9-06f8642343ae)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
