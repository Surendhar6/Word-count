# Word-count

## AIM:
To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:
Decleare number of words is 0

### Step 2: 
 Open it with txt file.
 
### Step 3: 
Give range for i.

### Step 4:  
Then nxt split the words.

### Step 5: 
Count the number of words.

### Step 6: 
Giving print statement for getting output.

## PROGRAM:

```
# Program to count the no. of words in a file.
# Developed by Surendhar A
# Reg.no: 212222110049
fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
  print("Number of words:",num_words)
  ```
  
### OUTPUT:
![Screenshot from 2023-06-09 08-35-50](https://github.com/Surendhar6/Word-count/assets/118352907/9a6f38b2-fcdf-4cde-b9af-319e04a9f67a)
![Screenshot from 2023-06-09 08-36-11](https://github.com/Surendhar6/Word-count/assets/118352907/e73da475-b16e-45e9-a0ff-de5d35c16f21)

## RESULT:
Thus the program is written to find the word count from a text.
