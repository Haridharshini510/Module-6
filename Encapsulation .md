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
```
class Rectangle:
    def __init__(self, length=5, breadth=3):
        self.__length = length      
        self.__breadth = breadth   

    def get_length(self):
        return self.__length

    def get_breadth(self):
        return self.__breadth

rect = Rectangle()

print(f"Length: {rect.get_length()}")
print(f"Breadth: {rect.get_breadth()}")

```
## Output
<img width="460" height="208" alt="image" src="https://github.com/user-attachments/assets/c26ca4b0-b902-4c3a-980b-64f676cd6b07" />

## Result
Thus, the program is executed successfully, demonstrating encapsulation by restricting direct access to private member variables.
