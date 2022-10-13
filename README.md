# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: give a user defined function as def ciculate()
### Step 2: give the value from the user for number of rotations
### Step 3: using slicing rotate the listGet the value from the user for the number of rotation
### Step 4: Using the slicing concept rotate the list
### Step 5: print the values
### Step 6: end the programme
## Program:
```python
#Program to circulate N values.
#Developed by:naveenaa A.K
#RegisterNumber:22003091
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n:]+a[:n]
    print("After circulating the values are: {}".format(a, n))
```
## Output:
![Screenshot from 2022-09-17 14-53-27](https://user-images.githubusercontent.com/113497406/190849866-c7b42a57-5986-4b7f-981f-6e853e09a31d.png)
## Result:
Thus the circulate n variables are successfully executed
