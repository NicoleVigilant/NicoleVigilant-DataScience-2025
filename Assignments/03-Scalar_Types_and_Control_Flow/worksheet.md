# 📝 Worksheet: 03 - Scalar Types and Control Flow

Use this worksheet to reinforce your understanding of variables, comparisons, and decision logic.

---

## 🧠 Section 1: Scalar Types

1. What is the output of the following code?

```python
x = 10
print(type(x))
```

`Answer:` <class 'int'>

2. What scalar type would best represent:
   - A person's name: str
   - Their age: int
   - Whether they passed a test: bool

---

### ✏️ Task: Type Practice

```python
# Create a variable for each type and print its value and type
age = 20

height = 5.6

name = "Nicole"

passed = True

print(age, type(age))

print(height, type(height))

print(name, type(name))

print(passed, type(passed))


output:
20 <class 'int'>

5.6 <class 'float'>

Nicole <class 'str'>

True <class 'bool'>

# Example: an int, float, str, and bool
```
---

## 🔁 Section 2: Comparison Operators

3. What does the `!=` operator mean?

`Answer:` not equal to

4. What will the following code print?

```python
a = 5
b = 3
print(a < b or b < 10)
```

`Answer:` true

---

## 🔀 Section 3: Control Flow

5. Write a conditional that prints "Pass" if a grade is >= 70, and "Fail" otherwise.

```python
# Your code:

grade = int(input("Enter your grade: "))

if grade >= 70:
    print("Pass")
else:
    print("Fail")

```

6. What does `elif` allow you to do?

`Answer:` Allows us to check multiple conditions after using if but before the final else

---

### ✏️ Task: Your Turn

Write a program that asks for the weather and prints:
- "Bring sunscreen" if it's sunny
- "Take an umbrella" if it's raining
- "Check the forecast" otherwise
- 
```python
weather = input("What’s the weather like today? ")

if weather.lower() == "sunny":
    print("Bring sunscreen")
elif weather.lower() == "raining":
    print("Take an umbrella")
else:
    print("Check the forecast")
```

