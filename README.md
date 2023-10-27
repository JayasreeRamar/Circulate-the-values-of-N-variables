# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Using concatentation operation display the entire rotated list
### Step 6: 
Stop the program
## Program:
```
#Program to circulate N values.
#Developed by: Jayasree R
#RegisterNumber:23009250
def circulate():
    n=eval(input())
    m=int(input())
    n=n[m:]+n[:m]
    print("After circulating the values are:",n)

```
## Output:
![OUTPUT](<To circulate the n variables-python programe problem.png>)
## Result:
Thus the python program for circulate the values of n variable is successfully executed.
