# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
# Step 1:

Open the file in read mode and handle it in test mood.
# Step 2:

Read the text using read() function.
# Step 3:

Split the text using space separator.We assume that words in a sentance are separted by a space character.
# Step 4:

The length of the split list should equal the numbers of words in the test file.
# Step 5:

You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
# Step 6:

End the program.




## PROGRAM:
```
# Program to count the no.of word count
# Developed by : Goutham.K
# Register Number : 212223110019
fname=input("Enter the file name ")
word_count=0
with open(fname,'r') as fp:
    for line in fp:
        words = line.split()
        word_count+=len(words)
    print("Number of words:",word_count)

### OUTPUT:
![image](https://github.com/Goutham2306/Word-count/assets/138971154/9bf95c6d-12bf-4f31-a8c0-76d7424a1cde)




## RESULT:
Thus the program is written to find the word count from a text.
