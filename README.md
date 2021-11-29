# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points

## ALGORITHM:

### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2:
 Get the input for list 1 and 2
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.jpg)
### Step 4: 
Print the distance
### Step 5: 
End the program

### PROGRAM:
~~~
import numpy as np
l1=[10,6]
l2=[4,2]
distance=np.sqrt(((l1[0]-l2[0])**2)+((l1[1]-l2[1])**2))
print("{:.2f}".format(distance))
~~~
  
### OUTPUT:
![output](dist.png)

### RESULT:
Thus the distance is successfully calculated

