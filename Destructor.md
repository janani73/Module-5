# Exp.No:5b
## Destructor-Demonstration of Constructor and Destructor in a Python Class


### AIM  
To write a Python program that illustrates how a constructor is executed when an object is created and how a destructor is called when the object is deleted.

### ALGORITHM
```
1.Start the program.
2.Define a class named Employee.
3.Inside the class, create a non-parameterized constructor __init__(self) that prints a message indicating that an employee object has been created.
4.Define a destructor method __del__(self) that prints a message when the employee object is deleted.
5.Create an object s of the class Employee, which automatically triggers the constructor and displays the creation message.
6.Explicitly delete the object s using the del statement, which invokes the destructor.
7.End the program after the destructor message is displayed.
```

### PROGRAM

```
class Employee:
    def __init__(self):
        print("Employee created.")
    def __del__(self):
        print("Destructor called, Employee deleted.")
s=Employee()
del s
```

### OUTPUT
<img width="1200" height="301" alt="image" src="https://github.com/user-attachments/assets/d8e5b7a0-157c-4647-9682-649ef5c95781" />


### RESULT
The program successfully shows how a constructor runs when an object is created and how the destructor is automatically called when the object is deleted, demonstrating object lifecycle in Python.
