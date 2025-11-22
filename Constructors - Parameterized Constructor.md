# Exp.No:5a
## Constructors - Implementing a Non-Parameterized Constructor and Method in a Python Class
### AIM  
To write a Python program that demonstrates the use of a non-parameterized constructor and a method to display a message using user input.

### ALGORITHM
```
1.Start the program.
2.Define a class named student.
3.Inside the class, create a non-parameterized constructor __init__() that prints a message indicating that the constructor has been called.
4.Define a method display(self, name) that prints a greeting message including the given name.
5.Ask the user to enter their name and store it in the variable name.
6.Create an object s of the class student, which automatically triggers the constructor and prints the constructor message.
7.Call the display() method using the object and pass the user-entered name as an argument.
8.Print the final output and end the program.
```

### PROGRAM

```
class student:
    def __init__(self):
        print("This is non parametrized constructor")
    def display(self,name):
        print(f"Hello {name}")
name=input()
s=student()
s.display(name)
```

### OUTPUT
<img width="1192" height="366" alt="image" src="https://github.com/user-attachments/assets/d57f1a3f-ed5b-4c86-9570-b6692a3ecec4" />


### RESULT
The program successfully displays a constructor message when the object is created and then prints a personalized greeting using the name provided by the user.
