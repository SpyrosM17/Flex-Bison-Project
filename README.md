# 🚀 ByteSpice: Lexical & Syntactic Analyzer

ByteSpice is a comprehensive **Lexical (Flex)** and **Syntactic (Bison)** analyzer designed for a custom object-oriented programming language.

## 🛠️ Features

* **Lexical Analysis:** Token recognition, keyword identification, and handling of numeric literals (`int`, `double`). Includes robust comment management using **Flex**.
* **Syntactic Analysis:** Implementation of a formal **BNF grammar** to support:
    * Control structures (`IF`, `WHILE`, `FOR`).
    * Class definitions and method declarations.
* **Symbol Table:** Dynamic management of variables and methods, featuring scope handling and duplicate declaration detection.
* **Semantic Checks:** Static analysis including:
    * Strict **type checking**.
    * Error detection (e.g., division by zero).
* **Operations Support:** Evaluation of basic arithmetic expressions and assignment operations.

## 💻 Tech Stack

* **C** (Core Logic & Data Structures)
* **Flex** (Lexical Scanner Generator)
* **Bison** (LALR Parser Generator)
