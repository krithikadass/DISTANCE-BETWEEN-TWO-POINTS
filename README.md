# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import the math module to use the square root function.
### Step 2: 
Define a function dis that takes four arguments: x1, y1, x2, and y2.
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Calculate the distance between the two points using the distance formula.
### Step 5: 
Return the calculated distance.
### PROGRAM:
```
#Program Developed By: M.Krithika Lakshmi
#Register Number: 212224230134

import math
def dis(x1,y1,x2,y2):
    d=((x2-x1)**2+(y2-y1)**2)
    g=math.sqrt(d)
return g
x1=4
x2=10
y1=2
y2=6
g=dis(x1,y1,x2,y2)
print("{:.2f}".format(g))
  
```

### OUTPUT:

![Screenshot 2025-05-07 140051](https://github.com/user-attachments/assets/fa966235-3329-4651-8f91-42d2ddd23e61)


### RESULT:
Thus the distance between two points found successfully by executing the python code.
