# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2: 
 Pass the filename as the first argument after the name of script.Open the file as sys.argv[1]
### Step 3: 
Read the file using read() method.
### Step 4:  
Use split() method to split the file content into words.
### Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to determine the number of words in the file created.
## PROGRAM:
Developed by: Tanushree.A
Registered number:23004953

import sys
file=open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))

### OUTPUT:

![op command](https://github.com/Tanug25/command-line-arguments-to-count-word/assets/138849166/a8046ca3-86d7-4c6f-ba6f-0bbedb72de03)
![op command 2](https://github.com/Tanug25/command-line-arguments-to-count-word/assets/138849166/27e11ac6-5ac5-4b22-88bb-efc5b18b8437)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
