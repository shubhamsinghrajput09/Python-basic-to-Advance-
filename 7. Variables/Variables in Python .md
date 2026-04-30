# 🐍 Python Variables

---

## 📌 Introduction

Variables are **containers used to store values** in Python.

- The value can be anything:
  - Numbers  
  - Strings  
  - Lists, etc.

---

## ⚡ Key Points

- No need to declare variables before using them  
- No need to specify data types  
- A variable is created when you assign a value to it  
- A variable is a **name given to a memory location** :contentReference[oaicite:0]{index=0}  

---

## 🧠 Example

```python
a = 1
b = "Jenny"
```

- `a` stores an integer value  
- `b` stores a string value  

```python
print(a)  # Output: 1
print(b)  # Output: Jenny
```

---

## 💡 Real-Life Example

Think of saving phone numbers:

Instead of remembering numbers directly, we store them with names.

```
Jenny → 9772812345
```

In programming:

```python
Jenny = 9772812345
```

Here, `Jenny` is a variable storing the phone number.

---

## 🔄 Variables Can Change

Variables can store different values over time.

```python
name = "Jenny"
print(name)

name = "Jiya"
print(name)
```

### ▶️ Output

```
Jenny
Jiya
```

---

## 🧪 Exercise

### 🎯 Problem

Calculate the length of a given name.

---

### 💻 Code

```python
name = input("What is your name? ")
length = len(name)

print(length)
```

---

### ▶️ Output

```
What is your name? Jenny
5
```

---

## 📝 Note

- `len()` is a function used to calculate the length of a string :contentReference[oaicite:1]{index=1}  

---

## 🚀 Conclusion

- Variables store data  
- No need for type declaration in Python  
- Values can change anytime  
- Useful for storing and managing data  

---

⭐ *Practice using variables with different data types to improve your understanding!*