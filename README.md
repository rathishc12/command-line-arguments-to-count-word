# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open vscode.
### Step 2: 
Type the program.
### Step 3: 
save the python file.
### Step 4: 
create a text file .
### Step 5: 
Run the program in the vscode, in the terminal type the following commands.
### Step 6: 
end the program

## PROGRAM:
```
#Developed by: Rathish kumar C
#Reference no: 22009283
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
```

### OUTPUT:

![cmdarg](https://user-images.githubusercontent.com/120539398/214832849-638b8c78-7686-484e-83c2-262b3fe1c024.png)
![cmdarg2](https://user-images.githubusercontent.com/120539398/214832151-e2b98ad8-6300-4bdf-97ef-49698ac7c302.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
