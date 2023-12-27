# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
get the input from the user
### Step 2: 
type the function to circulate the values
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
print the circulated values
### Step 6: 
end the program
## Program:
```
#Program to circulate N values.
#Developed by: Nirosha M
#RegisterNumber:23014438
def circulate():
    a=eval(input())
    n=int(input())
    c=a[n:]+a[:n]
    print("After circulating the values are:",c)
```
## Output:
![Alt text](image.png)
## Result:
Thus the circulate the values of n variable are executed successfully
