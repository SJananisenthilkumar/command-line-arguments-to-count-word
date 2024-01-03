# Command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program
### Step 2: 
 Import the file
### Step 3: 
Open the file
### Step 4:  
Write the function to count the words
### Step 5: 
Print the file
### Step 6: 
End the program
## PROGRAM:
```
#Program to find the word count using command line argument
#Dveloped by: JANANI
#reference Number:23013409
fname=input("enter the file name")
num_words=0
with open(fname,'r')as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print('Number of words: ',num_words)
```
### OUTPUT:
![image](https://github.com/SJananisenthilkumar/command-line-arguments-to-count-word/assets/144871139/73f29b14-cdd6-4243-8d50-8a6536658940)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
