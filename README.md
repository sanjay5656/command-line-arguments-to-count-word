# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module

### Step 2:
Open the file with sys.argv[1]

### Step 3:
Use the for loop to select the content in file

### Step 4:
Use split function to to separate the file content into words or strings

### Step 5:
Count the length of the words using len

### Step 6:
Print the number of words

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: Sanjay S
Register no : 212221243002
```
```
import sys
fp=open(sys.argv[1],'r')
d={}
for i in fp:
   for w in i.split():
      if w in not in d.keys():
         d[w]-1
      else:
         d[w]+=1
print(d)
```
### OUTPUT:
![image](https://github.com/sanjay5656/command-line-arguments-to-count-word/assets/115128955/cf8e1bbb-2ab6-4dc8-97db-a342668ab267)

![image](https://github.com/sanjay5656/command-line-arguments-to-count-word/assets/115128955/cbaffd56-c546-47d1-92cd-47c20139c843)

![image](https://github.com/sanjay5656/command-line-arguments-to-count-word/assets/115128955/05d2484f-4710-4850-a51d-fcf1642ab35c)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
