# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
#Developed by: JAYAMANI R
#Reference no: 22008124
import sys
count={}
a=sys.argv[1]
with open(a,'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word]=1
            else:
                count[word]+=1
print(count)
f.close()

### OUTPUT:

![cmdarg](https://user-images.githubusercontent.com/120539398/214832093-063a3392-341a-4080-8793-9cda854772e5.png)
![cmdarg2](https://user-images.githubusercontent.com/120539398/214832151-e2b98ad8-6300-4bdf-97ef-49698ac7c302.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
