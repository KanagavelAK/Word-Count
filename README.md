# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np

### Step 2: 
 Enter the input values
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments
### Step 4:  
Run the program
### Step 5: 
Input the values
### Step 6: 
End the program
## PROGRAM:
```python
program to find the number of words in a text file
Developed by : Kanagavel A K
Register number : 212223230096

num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```

### OUTPUT:
![9th python](https://github.com/KanagavelAK/Word-Count/assets/151514454/756ccfc2-5421-4fd8-b2da-178759180ee2)




## RESULT:
Thus the program is written to find the word count from a text.
