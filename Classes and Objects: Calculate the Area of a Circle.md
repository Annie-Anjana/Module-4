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
Add code here
```
import math
radius = float(input("Enter the radius of the circle: "))
class cse:
    def mech(self, r):
        area = math.pi * r ** 2
        print(f"Area of the circle with radius {r} is: {area:.2f}")
obj = cse()
obj.mech(radius)
```
## Output
![Screenshot 2025-04-30 203624](https://github.com/user-attachments/assets/8951138f-9d38-47c7-b162-90ea02b3a6a0)
## Result
The code executed successfully.
