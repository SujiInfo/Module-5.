# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program

```
class Student:
    def __init__(self,name,userid):
        self.name=name
        self.userid=userid
        self.display()
    def display(self):
        print(self.userid)
name=input()
userid=input()
obj = Student(name,userid)
obj.display()      

```

## Output
<img width="1096" height="429" alt="image" src="https://github.com/user-attachments/assets/6b835b71-2e45-49e8-bcd8-44a870881d88" />

## Result
The Python program that creates a Student class with a default constructor,which will take the name and userid of the person as parameters print the userid of the person.
