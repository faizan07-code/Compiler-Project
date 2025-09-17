# Compiler-Project
# 📝 Lexical Analyzer Project

This project implements a **Lexical Analyzer** in Python. It scans an input source code file and classifies tokens such as **keywords, identifiers, numbers, operators, and punctuation**. The results are written to an output file.

## 🚀 Features

* Tokenizes source code into meaningful units
* Supports detection of:

  * **Keywords** (e.g., `if`, `else`, `for`, `class`, etc.)
  * **Identifiers** (variables, function names, etc.)
  * **Numbers** (integers, floats, scientific notation)
  * **Operators** (`+`, `-`, `*`, `/`, `==`, `++`, etc.)
  * **Punctuation & delimiters** (`{}`, `()`, `;`, etc.)
* Uses **regular expressions** for token classification
* Outputs tokens into a structured text file

## 📂 Project Structure

```
├── main.py        # Main program for lexical analysis
├── source.txt     # Input source code file
├── output.txt     # Tokenized output file
├── Project.docx   # Project report/documentation
└── README.md      # Project description
```

## 🛠️ Requirements

* Python 3.x
* No external dependencies (uses only built-in `re` module)

## ▶️ Usage

1. Place your input code in `source.txt`.
2. Run the program:

   ```bash
   python main.py
   ```
3. The tokenized output will be generated in `output.txt`.

## 📜 Example

**Input (`source.txt`)**

```cpp
int x = 10;
if (x > 5) {
    x = x + 1;
}
```

**Output (`output.txt`)**

```
Keyword: int
Identifier: x
Operator: =
Number: 10
Keyword: if
Punctuation: (
Identifier: x
Operator: >
Number: 5
Punctuation: )
...
```

## 🎯 Applications

* Compiler design learning projects
* Preprocessing and tokenizing code
* Teaching **lexical analysis concepts** in programming languages

---
