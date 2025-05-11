# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```c
class Rectangle:
    def __init__(self):
        self.__length = 0
        self.__breadth = 0
    def set_dimensions(self, length, breadth):
        self.__length = length
        self.__breadth = breadth
    def get_area(self):
        return self.__length * self.__breadth
rect = Rectangle()
rect.set_dimensions(10, 5)
print("Area of Rectangle:", rect.get_area())
```
## Output
```c
Area of Rectangle: 50
```
## Result
The program successfully implements encapsulation by using private variables and public methods to set and get data.
