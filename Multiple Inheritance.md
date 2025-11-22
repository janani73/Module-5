# Exp.No:5e 
## Multiple Inheritance - Implementing Parameterized Constructor, Method, and Destructor in a Python Class

### AIM  
To write a Python program that uses a parameterized constructor to store student details, displays the details using a class method, and demonstrates how a destructor is called when the object is deleted.

### ALGORITHM

```
1.Start the program.
2.Define a class named Student.
3.Create a parameterized constructor __init__(self, name, age) that stores the name and age in instance variables.
4.Define a method printDetail(self) that prints the student’s name and age in a formatted sentence.
5.Define a destructor __del__(self) that prints a message when the object is deleted.
6.Create an object s1 of the Student class by passing the name "Vishvajit Rao" and age 22 to the constructor.
7.Call the method s1.printDetail() to display the stored details.
8.Allow the program to end, after which the destructor message is displayed automatically or when the object is deleted.
9.End the program.
```

### PROGRAM

```
class Student:
	def __init__(self, name, age):
		self.name = name
		self.age = age

	def printDetail(self):
		print(f"My name is {self.name} and I am {self.age} years old.")
	def __del__(self):
	    print("Vishvajit Rao student is deleted.")
s1 = Student("Vishvajit Rao", 22)
s1.printDetail()
```

### OUTPUT
<img width="1197" height="292" alt="image" src="https://github.com/user-attachments/assets/1a3e036f-daf8-4276-9431-af74bf42e1be" />


### RESULT
The program successfully creates a student object using a parameterized constructor, prints the student’s details using a class method, and displays a destructor message when the object is removed.




