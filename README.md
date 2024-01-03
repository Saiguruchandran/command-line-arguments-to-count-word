# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.
### Step 2: 
Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.
### Step 4:  
The length of the split list should equal the numbers of words in the test file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.

## PROGRAM:
```

#Developed by: SAI GURUCHANDRAN G
#Register Number: 23014037
fname=input("Enter the File Name: ")
num=0
with open(fname,'r') as file:
    for line in file:
        word=line.split()
        num+=len(word)
print("Number of Words: ",num)
```
### OUTPUT:

![WhatsApp Image 2024-01-02 at 23 52 57_70ed286d](https://github.com/Saiguruchandran/command-line-arguments-to-count-word/assets/144870946/b4837f7c-3017-4b7a-a4fb-2c2cff36a590)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
