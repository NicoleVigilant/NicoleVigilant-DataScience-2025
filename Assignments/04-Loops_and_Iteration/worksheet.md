# 📝 Worksheet: 04 - Loops and Iteration

Practice and reflect on how loops work in Python.

---

## 🔁 Section 1: For Loops

1. What does `range(5)` produce?

`Answer:` 0 1 2 3 4 

2. Write a `for` loop that prints numbers 1 to 10, but skips 5.

```python
# Your code:
for i in range(1, 11):
    if i == 5:
        continue
    print(i)
```

---

## 🔁 Section 2: While Loops

3. What’s the difference between a `for` loop and a `while` loop?

`Answer:` A for loop runs a specific number of times(used when we know how many iterations),
while a while loop runs as long as a condition is true(used when we dont know how many iterations).

4. What happens if a `while` loop's condition never becomes `False`?

`Answer:` It becomes an infinite loop

---

### ✏️ Task: Countdown with While

```python
# Use a while loop to count down from 5 to 1.

count = 5
while count >= 1:
    print(count)
    count -= 1

```

---

## 📁 Section 3: File Reading and `with`

5. What does the `with` statement do when opening a file?

`Answer:` It opens and closes a file automatically

6. How do you loop over each line in a file?

`Answer:` We use for line in file: print(line)

---

### ✏️ Task: File Filter

Write code that prints only the lines in a file that contain the word `"error"`.

```python
# Your code here
with open("log.txt", "r") as file:
    for line in file:
        if "error" in line:
            print(line.strip())

```
