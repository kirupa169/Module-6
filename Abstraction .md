# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

```
from abc import ABC
class Shape(ABC):
def calculate_area(self):
Pass
class Rectangle(Shape):
length = 5
breadth =3
def calculate_area(self):
print("Area of a rectangle:",self.length * self.breadth) class
Circle(Shape):
radius = 4
def calculate_area(self):
print("Area of a circle:",3.14 * self.radius * self.radius)
a=Rectangle()
b=Circle()
a.calculate_area()
b.calculate_area()
```
## Output
<img width="602" height="188" alt="image" src="https://github.com/user-attachments/assets/ac0e18db-3f8b-4a49-9f6c-e6a376fe76d1" />


## Result
 Thus, the program has been successfully executed.
