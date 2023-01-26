# Word-count

## AIM:
To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python3.7

ALGORITHM:
Step 1:
To write a python program for getting the word count from a text file

Step 2:
Open the required file by using the function "with"

Step 3:
Then use tha laptop to assign the i value in the file

Step 4:
Using split function to split the words

Step 5:
Finding the given length of the words by using len() function

Step 6:
Calling the function and Printing the number of word
## PROGRAM:
```
#Developed by : K.NIVETHA
#Reference number: 22009186
num=0
with open("git.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```

### OUTPUT:




## RESULT:
Thus the program is written to find the word count from a text.
