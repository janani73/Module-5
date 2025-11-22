# Exp.No:5d
## Multi-level Inheritance - Displaying Personal Details Using Multiple Methods in a Python Class

### AIM  
To write a Python program that uses a class with separate methods to print a person’s name, age, and salary.
### ALGORITHM
```
1.Start the program.
2.Define a class named name that contains three methods:
  Name(self, n) to print the person’s name,
  Age(self, a) to print the person’s age,
  Salary(self, s) to print the person’s salary.
3.Accept the person's name as string input from the user.
4.Accept the age and convert it to an integer.
5.Accept the salary and convert it to an integer.
6.Create an object of the class name.
7.Call the Name() method with the user-entered name.
8.Call the Age() method with the age.
9.Call the Salary() method with the salary.
10.Display all the outputs in a single line.
11.End the program.
```

### PROGRAM

```
class name():
    def Name(self,n):
        print(n,end=" ")
    def Age(self,a):
        print(a,end=" ")
    def Salary(self,s):
        print(s,end=" ")
n=input()
a=int(input())
s=int(input())
obj=name()
obj.Name(n)
obj.Age(a)
obj.Salary(s)

```

### OUTPUT
<img width="1210" height="320" alt="image" src="https://github.com/user-attachments/assets/803bc4e1-877e-4f93-8a69-7f5a62f06642" />


### RESULT
