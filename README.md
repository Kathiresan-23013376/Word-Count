# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define a function which will count the word in the given file.
### Step 2: 
Create a file pointer and open the file.
### Step 3: 
Initialize word count as zero.
### Step 4:  
For each line in file, split it into words and find number of the words in every line.
### Step 5: 
Sum the number of words in each line.
### Step 6: 
Display the total words in the file.
### Step 7:
Close the file pointer and end the program.
## PROGRAM:
```
Developed by: Kathiresan K
Register no: 212223110021
```
```py
def wordcount(filename):
    fp=open(filename)
    wordcount=0
    for i in fp:
        words=i.split()
        wordcount+=len(words)
    print("Total no of words in file is",wordcount)
    fp.close()
wordcount(input("Enter a filename in current directory or specify it with full path:"))
```
### OUTPUT:
![output](https://github.com/Kathiresan-23013376/Word-Count/assets/150008375/75d44d64-d9ec-4783-bacb-b53c8dae6268)



## RESULT:
Thus the program is written to find the word count from a text.
