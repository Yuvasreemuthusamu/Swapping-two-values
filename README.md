# Swapping-two-values
## AIM:
To write a python program for swapping of two values
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the two values from the user
### Step 2: 
Assign the value of second variable to a temporary variable 
### Step 3: 
Assign the value of the first variable to the second variable.
### Step 4:  
Assign the value in temporary variable to the first variable
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## PROGRAM:
```
# Program to swap two values.
# Developed by:Yuva Sree M 
# RegisterNumber:23013768
def swap (a,b):
    c=a
    a=b
    b=c
    return c,a,b
a=input()
b=input()
c=swap(a,b)
print('Swapped values are: {} {}'.format(b,a))
```
## Output:
(![OUTPUT](<Screenshot 2023-10-20 091625.png>))

## RESULT:
Thus the swapping of two values are successfully executed



