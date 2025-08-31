reh
[python_notes.md](https://github.com/user-attachments/files/22068094/python_notes.md)# 🐍 Python Notes

## 📌 Introduction  
Python is a **high-level, interpreted, object-oriented** programming language.  
- Easy to read & write  
- Widely used in web development, data science, AI, automation, and more  

---

## 🛠️ Python Basics  

### Printing
```python
print("Hello, World!")
```

### Variables & Data Types
```python
name = "Saniya"   # string
age = 21          # integer
height = 5.4      # float
is_student = True # boolean
```

### Type Casting
```python
x = int("10")   # 10
y = float(5)    # 5.0
z = str(25)     # "25"
```

---

## 🔄 Control Flow  

### If-Else
```python
num = 10
if num > 0:
    print("Positive")
elif num == 0:
    print("Zero")
else:
    print("Negative")
```

### Loops
```python
# For loop
for i in range(5):
    print(i)

# While loop
count = 0
while count < 5:
    print(count)
    count += 1
```

---

## 📦 Functions
```python
def greet(name):
    return f"Hello, {name}"

print(greet("Saniya"))
```

---

## 📂 Data Structures  

### Lists
```python
fruits = ["apple", "banana", "cherry"]
fruits.append("mango")
print(fruits[0])  # apple
```

### Tuples
```python
coordinates = (10, 20)
print(coordinates[1])  # 20
```

### Sets
```python
unique = {1, 2, 3, 3}
print(unique)  # {1, 2, 3}
```

### Dictionaries
```python
student = {"name": "Saniya", "age": 21}
print(student["name"])  # Saniya
```

---

## 🧱 Object-Oriented Programming (OOP)

```python
class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    
    def greet(self):
        print(f"My name is {self.name} and I am {self.age} years old")

s1 = Student("Saniya", 21)
s1.greet()
```

---

## 📑 File Handling
```python
# Writing
with open("test.txt", "w") as f:
    f.write("Hello, World!")

# Reading
with open("test.txt", "r") as f:
    print(f.read())
```

