# Word-count

## AIM:

To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 

PC
Anaconda - Python 3.7

## ALGORITHM: 



### Step 1:

Import sys

### Step 2: 

Get the input values as given
 
### Step 3: 

Write a program for getting the word count from a text

### Step 4:  

Find the word count from a text

### Step 6: 

Emd the program

## PROGRAM:
```python

## Developed by: Pavithra R
## Register number:22008965

num_words =0
with open('python.py','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={0}".format(num_words))
```
### OUTPUT:
![](./word%20count.png)


## RESULT:
Thus the program is written to find the word count from a text.
