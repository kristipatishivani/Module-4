# Exp.No:17  
## EXCEPTION HANDLING

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

### ALGORITHM

1. Begin the program.  
2. Read a string input from the user containing grades separated by commas and store it in user_input.
3. Split the string into a list of grade strings using split(',') and store it in grades_str.
4. Use a try block to: Convert each grade in grades_str into an integer using list comprehension and store them in grades. Print the list grades.
5. If a ValueError occurs, print an error message and display the original grades_str.
6. Terminate the program.


### PROGRAM

```
Reg.No-212222060126
Name-Kristipati Shivani

user_input = input()
grades_str = user_input.split(',')
try:
    grades = [int(g) for g in grades_str]
    print(grades)
except ValueError:
    print("The grades you entered were in an invalid format.")
    print(grades_str)

```

### OUTPUT
<img width="1133" height="223" alt="image" src="https://github.com/user-attachments/assets/f10b0b74-a53d-41e0-ad38-c51fe0e011f7" />

### RESULT
Thus, a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers are verified.
