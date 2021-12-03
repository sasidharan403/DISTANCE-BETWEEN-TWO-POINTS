# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()


### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.jpg)
### Step 4:
End the program 
### Step 5: 
### PROGRAM:
  ~~~
  #Program to find the distance between two points.
#Developed by:A.sasidharan
#RegisterNumber:21004178
import numpy as np
p1=[10,6]
p2=[4,2]
distance=np.sqrt(((p1[0]-p2[0])*(p1[0]-p2[0]))+((p1[1]-p2[1])*(p1[1]-p2[1])))
print("{:.2f}".format(distance))
~~~

### OUTPUT:
![OUTPUT](https://github.com/sasidharan403/DISTANCE-BETWEEN-TWO-POINTS/blob/main/Screenshot%20(14).png?raw=true)

### RESULT:
Thus the distance between two points are successfully solved using python program