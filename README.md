# 🧾 Python File Handling Tasks

This repository contains two Python programs that demonstrate basic **file reading**, **writing**, and **appending** operations.  
These examples help understand how to work with files in Python using exception handling and user input.

---

## 📁 Project Structure

```
📦 Python-File-Handling
├── task1.py     # Read a file and handle errors
├── task2.py     # Write and append data to a file
└── README.md    # Project documentation
```

---

## 📘 Task 1: Read a File and Handle Errors (`task1.py`)

This program opens and reads a text file named **sample.txt**, printing its contents line by line.  
If the file does not exist, it displays an error message instead of crashing.

### 💻 Example Run
```
Reading file content:

Line 1: This is a sample text file.
Line 2: It contains multiple lines.
```

If the file is missing:
```
Error: The file 'sample.txt' was not found.
```

### 🧠 Concepts Used
- File handling (`open`, `read`)  
- Exception handling (`try-except`)  
- Looping with `enumerate()`  

---

## 📗 Task 2: Write and Append Data to a File (`task2.py`)

This program writes user input to a file named **output.txt**, appends additional text to it,  
and then reads and displays the complete file content.

### 💻 Example Run
```
Enter text to write to the file: Hello, Python!
Data successfully written to output.txt.

Enter additional text to append: Learning file handling in Python.
Data successfully appended.

Final content of output.txt:
Hello, Python!
Learning file handling in Python.
```

### 🧠 Concepts Used
- File writing (`w` mode)  
- File appending (`a` mode)  
- Reading file content (`r` mode)  
- User input (`input()`)  

---

## 🚀 How to Run

Make sure you have **Python 3.x** installed.

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/python-file-handling.git
   cd python-file-handling
   ```

2. Run any task file:
   ```bash
   python task1.py
   ```
   or
   ```bash
   python task2.py
   ```

---

## 🧾 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ✨ Author

**Saket Goswami**  
Learning Python step-by-step 🧩  

---

⭐ *If you found this helpful, don’t forget to star the repo on GitHub!*  
