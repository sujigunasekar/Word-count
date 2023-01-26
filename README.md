# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
```
Step 1:
Import sys

Step 2:
Get the input values as given

Step 3:
Write a program for getting the word count from a text

Step 4:
Find the word count from a text

Step 6:
Emd the program

## PROGRAM:
```
## Developed by: Suji.G
## Reference Number: 22008563
```
fname = input('Enter file name: ')
num_words = 0
with open(fname, 'r') as f:
    for line in f:
        words = line.split()
        num_words += len(words)
print('Number of words: ',num_words)
```

### OUTPUT:
![o22](https://user-images.githubusercontent.com/119559822/214848215-a69e7f55-c208-4860-a043-8c1768b501ad.png)
![o2](https://user-images.githubusercontent.com/119559822/214848606-ecde4923-94b2-44c6-a215-aee155e742da.png)








## RESULT:
Thus the program is written to find the word count from a text.
