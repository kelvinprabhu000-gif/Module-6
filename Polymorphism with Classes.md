# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
```pyclass Beans:
    def type(self):
        print("Vegetable")

    def color(self):
        print("Green")


# Class Mango
class Mango:
    def type(self):
        print("Fruit")

    def color(self):
        print("Yellow")


# Generic function
def func(obj):
    obj.type()
    obj.color()


# Create objects
b = Beans()
m = Mango()

# Call function
func(b)
func(m)
```
## Output
<img width="629" height="497" alt="image" src="https://github.com/user-attachments/assets/55239256-9546-4def-a205-7d1c5266530f" />

## Result
Thus, the Python program demonstrating polymorphism using a generic function was executed successfully, and the output obtained
