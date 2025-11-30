# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
```
class Marks:
    def __init__(self, mark):
        self.mark = mark

    def __lt__(self, other):
        return self.mark < other.mark

obj1 = Marks(20)
obj2 = Marks(10)

if obj1 < obj2:
    print("True")
else:
    print("False")

```
## Output
<img width="354" height="180" alt="image" src="https://github.com/user-attachments/assets/fac88112-086d-454f-be1f-1be2067873e0" />

## Result
Thus, the program is executed successfully, demonstrating operator overloading by customizing the behavior of the less than (<) operator for the Marks class.
