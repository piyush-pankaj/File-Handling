# 📂 Python File Handling Basics

This repository demonstrates fundamental concepts of file handling in Python, including reading and writing files using `open()` and `with open()` along with different file modes.

---

## 📁 Repository Structure

```
├── Machine_Learning_AI.txt   # Sample text file
├── file_handling.ipynb       # Jupyter Notebook with explanations and examples
```

---

## 📄 Files Description

### 📌 `Machine_Learning_AI.txt`

A sample text file used to perform various file operations such as:

* Reading content
* Writing data
* Appending new information

---

### 📓 `file_handling.ipynb`

This Jupyter Notebook covers:

* Introduction to file handling in Python
* Using `open()` function
* Using `with open()` (recommended approach)
* File modes:

  * `r` → Read
  * `w` → Write (overwrite)
  * `a` → Append
  * `x` → Create new file
* Writing data into files
* Best practices for file handling

---

## 🧠 Concepts Covered

### 1. Opening a File with `open()`

```python
file = open("Machine_Learning_AI.txt", "r")
content = file.read()
file.close()
```

⚠️ Always remember to close the file.

---

### 2. Using `with open()` (Best Practice)

```python
with open("Machine_Learning_AI.txt", "r") as file:
    content = file.read()
```

✅ Automatically handles file closing.

---

## ✍️ Writing to a File

```python
with open("example.txt", "w") as file:
    file.write("Hello, this is a sample text.")
```

---

## ➕ Appending to a File

```python
with open("example.txt", "a") as file:
    file.write("\nAdding more content.")
```

---

## 📌 File Modes Summary

| Mode | Description                       |
| ---- | --------------------------------- |
| `r`  | Read file                         |
| `w`  | Write (overwrite file)            |
| `a`  | Append to file                    |
| `x`  | Create new file (error if exists) |

---

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone <your-repository-link>
   ```

2. Navigate to the folder:

   ```bash
   cd <repository-folder>
   ```

3. Open the notebook:

   ```bash
   jupyter notebook
   ```

4. Run the notebook cells to explore file handling concepts.

---

## 🎯 Purpose

This repository is ideal for beginners who want to:

* Learn Python file handling step-by-step
* Understand different file modes
* Practice reading and writing files

---

## 📜 License

This project is open-source and free to use.

---
## Owner
- Piyush Pankaj
