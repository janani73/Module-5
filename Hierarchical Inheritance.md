# Exp.No:5c
## Hierarchical Inheritance - Employee Details Validation Using Tuple and Conditional Statement in Python


### AIM  
To write a Python program that accepts an employee ID and name, stores them as a tuple, and checks if the employee ID is valid based on a given condition.

### ALGORITHM

```
1.Start the program.
2.Accept an employee ID from the user and convert it to an integer.
3.Accept the employee name as a string input.
4.Create a tuple containing the employee ID and employee name.
5.Print the tuple on the same line using end=' '.
6.Check whether the employee ID is greater than 500000.
7.If the condition is true, print "Valid Employee".
8.If the condition is false, print "Invalid Employee".
9.End the program.
```
### PROGRAM
```
emp_id=int(input())
emp_name=input()
print((emp_id,emp_name),end='  ')
if emp_id > 500000:
    print("Valid Employee")
else:
    print("Invalid Employee")
```

### OUTPUT 

<img width="1202" height="368" alt="image" src="https://github.com/user-attachments/assets/505cd972-a5d7-458a-9cf8-fcef49a682d8" />


### RESULT
The program successfully reads employee details, stores them as a tuple, displays them, and classifies whether the employee is valid or invalid based on the employee ID.
