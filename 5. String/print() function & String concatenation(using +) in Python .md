# 📅 Day 5: `print()` Function & String Concatenation in Python

---

## 📌 Introduction

In this lesson, we will learn:
- How to use the `print()` function
- How to combine strings using **concatenation (`+`)**

---

## 🧠 `print()` Function Recap

The `print()` function is used to display output on the screen.

### ✅ Example

```python
print("Hello, World!")
```

---

## 🔗 String Concatenation

String concatenation means **joining two or more strings together** using the `+` operator.

---

## 💻 Syntax

```python
string1 + string2
```

---

## 📝 Examples

### 1. Basic Concatenation

```python
print("Hello " + "World")
```

### ▶️ Output
```
Hello World
```

---

### 2. Using Variables

```python
first_name = "John"
last_name = "Doe"

print(first_name + " " + last_name)
```

### ▶️ Output
```
John Doe
```

---

### 3. Concatenating Multiple Strings

```python
print("Python " + "is " + "fun!")
```

### ▶️ Output
```
Python is fun!
```

---

## ⚠️ Important Notes

- You can only concatenate **strings with strings**
- You cannot directly add numbers to strings

### ❌ Wrong Example

```python
print("Age: " + 20)
```

👉 This will cause an error

---

### ✅ Correct Way

```python
print("Age: " + str(20))
```

---

## 💡 Alternative (Better Way)

You can also use commas in `print()`:

```python
print("Age:", 20)
```

---

## 🧪 Practice Examples

```python
name = "Alice"
city = "Delhi"

print("My name is " + name)
print("I live in " + city)
```

---

## 🚀 Conclusion

- `print()` is used to display output  
- String concatenation joins strings using `+`  
- Always ensure both values are strings when using `+`  

---

⭐ *Practice combining different strings to get comfortable with concatenation!*
