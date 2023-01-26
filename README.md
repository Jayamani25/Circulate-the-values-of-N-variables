# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user 
### Step 2: 
Assign values in a variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5:
By using concatenation operator ,it will join the two values
### Step 6: 
print the output

## Program:
```
#Program to circulate N values.
#Developed by: R.Jayamani
#RegisterNumber: 22008124
circulate()
def circulate():
    l=eval(input())
    n=int(input())
    d=l[n:]+l[:n]
    print("After circulating the values are:",d)
```    

## Output:
![1](https://user-images.githubusercontent.com/85949888/214784316-4be79278-a473-4cb5-a1e2-b7e423a182cd.png)

## Result:
Circulate the n variables using function is successfully executed.
