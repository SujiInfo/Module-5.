# Multilevel Inheritance Example in Python

This Python project demonstrates the concept of **Multilevel Inheritance** to collect and display the **name**, **age**, and **location** of a person.

## 🎯 Aim

To write a Python program that uses multilevel inheritance to get and display a person’s name, age, and location.

## 🧠 Algorithm

1. **Parent Class**  
   - `__init__(name)` initializes the `name` attribute.  
   - `getName()` returns the `name`.

2. **Child Class (inherits Parent)**  
   - `__init__(name, age)` initializes `name` using `super()` and adds `age`.  
   - `getAge()` returns the `age`.

3. **Grandchild Class (inherits Child)**  
   - `__init__(name, age, location)` initializes `name` and `age` using `super()` and adds `location`.  
   - `getLocation()` returns the `location`.

4. **Input & Output**  
   - Take user input for name, age, and location.  
   - Create an instance of `Grandchild`.  
   - Print all details using class methods.

## Program
```
class student:
    def __init__(self,x,y,z):
        self.x=x
        self.y=y
        self.z=z
class s(student):
    def show(self):
        print(f"{self.x} {self.y} {self.z}")
x=input()
y=int(input())
z=int(input())
obj=s(x,y,z)
obj.show()
```

## Sample Output
<img width="1662" height="600" alt="image" src="https://github.com/user-attachments/assets/de5975a4-4cb1-4d02-b737-39ddfe3c2874" />

