# 📝 Worksheet: 02 - Working with Data

Use this worksheet to review and reinforce your understanding of Python data containers.

---

## 🧠 Section 1: Lists

1. What method adds an item to the end of a list?  
   `Answer:` append()

2. How can you remove an item from a list by value?  
   `Answer:` remove()

3. What’s the result of this code?

```python
nums = [2, 4, 6]
nums.append(8)
print(nums)
```

   `Answer:` 2,4,6,8

---

### ✏️ Task: List Practice

```python
# Create a list of your top 3 favorite foods.
foods = ["wings", "pasta", "tacos"]
# Add another food to the list.
foods.append("burgers")
# Remove one item and print the list.
foods.remove("pasta")
print(foods)

```

---

## 🔒 Section 2: Tuples

4. What is a key difference between a list and a tuple?  
   `Answer:` A list is mutable(content can be changed) while a tuple is immutable(content can't be changed).

5. Can you change the contents of a tuple once it is created? Why or why not?  
   `Answer:` No because tuples are immutable. the content can't be changed.

---

### ✏️ Task: Tuple Practice

```python
# Create a tuple with your favorite 3 numbers.
nums = (7, 14, 21)
# Unpack it into three variables and print each.
a, b, c = nums
print(a)
print(b)
print(c)
```

---

## 🔑 Section 3: Dictionaries

6. What does the `.get()` method do differently from accessing a key directly?  
   `Answer:` .get() returns  default value or zero if the key doesnt exist, while direct access causes a key error.

7. How do you loop through both keys and values in a dictionary?  
   `Answer:` use .items() in a for loop.

---

### ✏️ Task: Dictionary Practice

```python
# Create a dictionary with keys: 'name', 'age', and 'hobby'.
my_dict = {"name": "Nicole", "age": 20, "hobby": "reading"}

# Print each key and value in the format "key: value".
for key, value in my_dict.items():
    print(key, " : ", value)
```

---

## 🧾 Submit Checklist

- [x] I practiced creating and modifying lists.
- [x] I understand how tuples are different from lists.
- [x] I accessed and looped through dictionary items.
