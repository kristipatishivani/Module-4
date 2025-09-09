# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS


### AIM  
To write a Python program to perform addition and division operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`, and `div`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform division  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'


### ALGORITHM

1. Begin the program.  
2. Define a class cse with an init method to initialize two numbers a and b.
3. Define a method mod() to return the modulus of a and b.
4. Define a method div() to return the floor division of a by b.
5. Read two integer inputs from the user and create an object obj of the cse class.
6. Initialize choice as 1 and use a while loop to repeatedly ask the user for a choice.
7. If choice == 1, display the modulus result; if choice == 2, display the division result; otherwise, print "Exiting!".
8. Terminate the program.


### PROGRAM

```
Reg.No: 212222060126
Name: Kristipati Shivani

class cse:
    def __init__(self, a, b):
        self.a=a
        self.b=b
    def mod(self):
        return self.a%self.b
    def div(self):
        return self.a//self.b

a=int(input())
b=int(input())
obj=cse(a, b)
obj.mod()
obj.div()
choice=1
while choice!=0:
    choice=int(input())
    if choice==1:
        print("Result: ", obj.mod())
    elif choice==2:
        print("Result: ", obj.div())
    else:
        print("Exiting!")

print()

```

### OUTPUT
<img width="543" height="338" alt="image" src="https://github.com/user-attachments/assets/428f3537-b46d-48db-b6b2-7dd0daaaaee6" />

### RESULT
Thus the Python program to perform addition and division operations using a class was implemented and executed successfully.
