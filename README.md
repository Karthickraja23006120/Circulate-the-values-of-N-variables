# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
define the function
### Step 2: 
input the two variables
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
print the nth variable
### Step 6: 
end the program
## Program:
```
#Program to circulate N values.
#Developed by: Karthick Raja K
#RegisterNumber:23006120
def circulate():
    l=eval(input())
    n=int(input())
    result=l[n:]+l[:n]
    print("After circulating the values are:",result)
 ```
## Output:
![output](/Screenshot%202023-07-26%20102829.png)
![output](/Screenshot%202023-07-26%20102855.png)
## Result:
The nth value of a variable is printed using the function concept
