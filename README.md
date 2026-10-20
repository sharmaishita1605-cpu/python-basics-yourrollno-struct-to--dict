# python-basics-yourrollno-struct-to--dict
A simple Python program that converts a dataclass object into a dictionary using Python’s `dataclasses` module and the `asdict()` function.
# Struct to Dictionary Converter

## 📌 Project Description

This project demonstrates how to convert a Python dataclass object into a dictionary using the `dataclasses` module and its built-in `asdict()` function.

It is a beginner-friendly project that introduces Python dataclasses, object handling, and dictionary conversion.

## ✨ Features

- Defines structured data using Python dataclasses.
- Converts dataclass objects into dictionaries using `asdict()`.
- Provides a simple and readable implementation.
- Uses Python's built-in standard library.
- Suitable for beginners learning Python data structures.

## 📂 Project Structure

```text
struct-to-dict/
├── struct to dict.py
└── README.md
```

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone <YOUR_REPOSITORY_URL>
   ```

2. Navigate to the project directory:

   ```bash
   cd struct-to-dict
   ```

3. Ensure Python 3.7 or later is installed.

## 📋 Requirements

- Python 3.7 or later
- No external libraries required

The program uses the built-in `dataclasses` module, available in Python 3.7 and later.

## 🚀 Usage

Run the program from your terminal:

```bash
python "struct to dict.py"
```

If your system uses `python3`, run:

```bash
python3 "struct to dict.py"
```

The program will create a dataclass object, convert it into a dictionary, and print the result.

## 💻 Example

### Sample Code

```python
from dataclasses import dataclass, asdict

@dataclass
class Student:
    name: str
    age: int
    branch: str

student = Student("Ishita", 20, "CSE")

student_dict = asdict(student)

print(student_dict)
```

### Output

```text
{'name': 'Ishita', 'age': 20, 'branch': 'CSE'}
```

## 📚 Concepts Covered

- Python dataclasses
- Object creation
- Dictionary data structures
- The `asdict()` function
- Python standard library modules

## 📄 License

This project can be distributed under the MIT License. To apply this license, add a `LICENSE` file containing the MIT License text and update the repository's license information accordingly.

---

