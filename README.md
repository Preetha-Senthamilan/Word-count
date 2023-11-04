# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:

Open then required file by using the function"with"

Step 2:

Using split function to split the words.

Step 3:

Finding the length of the words by using len() function.

Step 4:

Calling the function and printing the number of words.

## PROGRAM:
```
#Developed By: PREETHA.S
#Register No: 212222230110
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of words:",wordslen)

```
### OUTPUT:

i)

![Screenshot 2023-11-04 180221](https://github.com/Preetha-Senthamilan/Word-count/assets/119390282/dc1d31b0-08c6-424c-8ba8-f48cc48aa0f5)

ii)

![Screenshot 2023-11-04 180848](https://github.com/Preetha-Senthamilan/Word-count/assets/119390282/38bfa3ff-9b65-4068-8eef-a2336e3d25c0)


## RESULT:
Thus the program is written to find the word count from a text.
