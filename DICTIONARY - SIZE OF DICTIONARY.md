# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY

### AIM  
To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.


### ALGORITHM

1. Begin the program.  
2. Import the `sys` module to use the `getsizeof()` function.  
3. Define the dictionaries with key-value pairs (`dic1`, `dic2`, `dic3`).  
4. Use `sys.getsizeof()` to calculate the memory size of each dictionary.  
5. Print the size of each dictionary in bytes.  
6. Terminate the program.

### PROGRAM

```
#Reg.No-212222060126
#Name-Kristipati Shivani

from sys import getsizeof
dic1 = {"A": 1, "B": 2, "C": 3}
dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}
result1 = getsizeof(dic1)
result2 = getsizeof(dic2)
result3 = getsizeof(dic3)
print("Size of dic1: ", result1, "bytes", sep='')
print("Size of dic2: ", result2, "bytes", sep='')
print("Size of dic3: ", result3, "bytes", sep='')

```

### OUTPUT
<img width="674" height="203" alt="image" src="https://github.com/user-attachments/assets/866d6a6e-69d0-495d-acd6-5cc61d8252d6" />

### RESULT
Thus, a Python program to print the size of a dictionary using getsizeof() from the sys module are verified.
