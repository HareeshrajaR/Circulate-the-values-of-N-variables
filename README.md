## DATE:
## EXP NO:2 Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
print the result
## Program:


### Developed by:HAREESH R
### Register no:212223230068
```
def circulate():
    values=eval(input())
    n=int(input())
    for i in range(n):
        temp=values.pop(0)
        values.append(temp)
    print("After circulating the values are:",values)



```
## Output:

![Screenshot 2024-08-26 212102](https://github.com/user-attachments/assets/9716319a-08f6-479e-9e10-6f9893d797b8)

## Result:
The output for circulate the values of n variables is successfull.
