# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Assume the keyword to run the program

### Step 2: 
Assing the value of the first variable

### Step 3: 
Get the value from the user for the number of rotation

### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
using the slicing concept rotate the list withthe denote of the first variable

### Step 6: 
print the values of the first variable
## Program:
```
#Program to circulate N values.
#Developed by: sarguru
#RegisterNumber:22002828
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```


## Output:
![output](./circulate%20n%20variable.png)



## Result:
thus the circulating of the first varible is successfully executed

