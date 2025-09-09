# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

### AIM  
Write Python Program to take the radius from the user and find the area of the circle using class name 'pen' and function name 'stationary'

### ALGORITHM

1. Begin the program.  
2. Create a class named `umbrella`.  
3. Define a method `rain(self, r)` inside the class `umbrella` that accepts a radius `r` as an argument.  
4. Inside the `rain` method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times r^2 \]  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `umbrella` class and store it in the variable `u`.  
7. Call the `rain` method of the `umbrella` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.


### PROGRAM

```
Reg.No: 212223060305
Name: Vishnu Priya E

class pen:
    r=int(input())
    a=3.141592*(r**2)
    def stationary(self):
        print(f"Area of circle: {round(self.a,2)}")
obj=pen()
obj.stationary()

```

### OUTPUT

<img width="967" height="296" alt="image" src="https://github.com/user-attachments/assets/12d0b827-0c9a-48b2-b23f-2b6714673d72" />

### RESULT

Thus,a Python program to take the radius from the user and find the area of a circle are verified.



