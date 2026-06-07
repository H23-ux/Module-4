# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
from math import pi
class cse():
    def __init__(self):
        pass
    def mech(self,r):
        print('Area of circle:',round(pi*r*r,2))
a=cse()
a.mech(int(input()))
```
## Output

<img width="602" height="287" alt="image" src="https://github.com/user-attachments/assets/bfc14463-5512-4057-ad46-4d5c49836df4" />

## Result
The Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation has been written and verified.
