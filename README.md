# Exp.No:19 CLASS AND OBJECTS - AREA OF CIRCLE
# AIM
To write a Python program to take the radius from the user and find the area of a circle using the class name umbrella and function name rain.

# ALGORITHM
Begin the program. Create a class named umbrella. Define a method rain(self, r) inside the class umbrella that accepts a radius r as an argument. Inside the rain method: Calculate the area of a circle using the formula: [ \text{Area} = \pi \times r^2 ] Use the math.pi constant to get the value of π and perform the calculation. Print the result, formatted to two decimal places. Prompt the user for an integer input to represent the radius of the circle. Create an instance of the umbrella class and store it in the variable u. Call the rain method of the umbrella class, passing the user-provided radius r as an argument. Terminate the program.

# PROGRAM
REG No: 212222060126 NAME : Kristipati shivani

class umbrella:
      a=0
      def find(self,a):
          a=3.141592*a*a
          print("Area of circle: {:.2f}".format(a))
b=area()
c=int(input())
b.find(c)
# OUTPUT
<img width="950" height="291" alt="image" src="https://github.com/user-attachments/assets/6e07248b-677d-4957-bb1f-59b87679d43a" />

# RESULT
Thus ,the Python program to take the radius from the user and find the area of a circle using the class name umbrella and function name rain is successfully done.

# Exp.No:16 DICTIONARY - SIZE OF DICTIONARY
# AIM
To write a Python program to print the size of a dictionary using getsizeof() from the sys module.

# ALGORITHM
Begin the program. Import the sys module to use the getsizeof() function. Define the dictionaries with key-value pairs (dic1, dic2, dic3). Use sys.getsizeof() to calculate the memory size of each dictionary. Print the size of each dictionary in bytes. Terminate the program.

# PROGRAM
REG No: 212222060126 NAME: Kristipati shivani

import sys
dic1 = {"A": 1, "B": 2, "C": 3} 

dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}

dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}

size_dic1=sys. getsizeof(dic1)
size_dic2=sys. getsizeof(dic2)
size_dic3=sys. getsizeof(dic3)

print("Size of dic1: "+str(size_dic1) +"bytes")
print("Size of dic2: "+str(size_dic2) +"bytes")
print("Size of dic3: "+str(size_dic3) +"bytes")
# OUTPUT
<img width="934" height="242" alt="image" src="https://github.com/user-attachments/assets/328424f0-a72a-404e-94f3-4189dd91d81f" />

# RESULT
Thus, the Python program to print the size of a dictionary using getsizeof() from the sys module is successfully done.

# Exp.No:17 EXCEPTION HANDLING
# AIM
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

# ALGORITHM
Begin the program. Read a string input_str from the user using input(). Split the input string using commas (,) to create a list of grades. Use a try block to attempt converting each item in the grades list to an integer and store the result in l1. If the conversion is successful, print the list l1 containing the integer values. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: "The grades you entered were in an invalid format." along with the original grades list. Terminate the program.

# PROGRAM
REG No: 212222060126 NAME: Kristipati shivani

grades = input().split(",")

try:
	grades = [int(grade) for grade in grades]
  
except ValueError:
	print("The grades you entered were in an invalid format.")
print(grades)
# OUTPUT
<img width="1332" height="312" alt="image" src="https://github.com/user-attachments/assets/aa2cee47-37ad-4692-b73b-b24650d7b4db" />

# RESULT
Thus the Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers is successfully verified.

# Exp.No:18 FILES - FREQUENCY OF CHARACTERS IN A FILE
# AIM
To write a Python program that reads a file and counts the frequency of each character in it.

# ALGORITHM
Begin the program. Define the function create_file() that accepts two arguments: file_path: The path to the file. content: The string content to be written into the file. Open the file specified by file_path in write mode ('w'), and write the provided content into the file. Close the file (this is automatically done when exiting the with block). Define the function character_frequency() that accepts one argument: file_path: The path to the file whose character frequency is to be calculated. Open the file specified by file_path in read mode ('r'), and read its content into the variable content. Initialize an empty dictionary (d1) to store the frequency of each character using defaultdict(int). Loop through each character in the content: For each character ch, increment its corresponding frequency in the dictionary d1. Return the dictionary d1, which contains the frequency of each character in the file. Terminate the program.

# PROGRAM
REG NO: 212222060126
NAME : Kristipati shivani
a=input()
b=input()
count=0
for i in a:
    if (i==b):
        count+=1 
print("Character "+b+" in the "+a+" is "+str(count)+" times")
# OUTPUT
<img width="1295" height="313" alt="image" src="https://github.com/user-attachments/assets/c0a77109-cca6-4b8f-aeb8-7996c1862dc9" />

# RESULT
Thus,the Python program that reads a file and counts the frequency of each character in it is successfully verified.

# Exp.No:20 SEB - ARITHMETIC CALCULATION USING CLASS
# AIM
To write a Python program to perform addition and division operations using a class. The class should be named Saveetha, and the function names should be setvalues (to set a and b values), add, and div. The program should handle the following cases: choice 1 → Perform addition choice 2 → Perform division choice 0 → Exit For other choices, print 'Invalid choice'

# ALGORITHM
Begin the program. Create a class Saveetha. Define the following methods inside the Saveetha class: init(self): Initializes a and b to zero. setvalues(self, a, b): Sets the values of a and b. add(self): Performs the addition operation. div(self): Performs the division operation. If b is zero, returns an error message for division by zero. Create a main() function. Take input from the user for the values of a and b using setvalues(a, b) method. Use a while True loop to repeatedly ask the user for a choice: If the choice is 1, call the add() method and print the result. If the choice is 2, call the div() method and print the result. Handle division by zero. If the choice is 0, print "Exiting!" and exit the loop. If the choice is not 1, 2, or 0, print "Invalid choice". Terminate the program.

# PROGRAM
REG NO : 212222060126 NAME : Kristipati shivani

class saveetha:
    def add(self,a,b):
        return a+b
    def div(self,a,b):
        return a//b
c=saveetha()
a=int(input())
b=int(input())
choice=1
while choice!=0:
    choice=int(input())
    if choice==1:
       print("Result: ",c.add(a,b))
    elif choice==2:
       print("Result: ",c.div(a,b))
    else:
        print("Exiting!")
# OUTPUT
<img width="747" height="458" alt="image" src="https://github.com/user-attachments/assets/85ed3b60-3e3a-4c8e-8206-9295f1cf9984" />

# RESULT
Thus the To write a Python program to perform addition and division operations using a class. The class should be named Saveetha, and the function names should be setvalues (to set a and b values), add, and div is successfully verified.
