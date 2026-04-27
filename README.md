# 📚 Library Management System

A Python-based Library Management System built using Object-Oriented Programming (OOP) concepts.

## 👩‍💻 Author
**S. Anusha**

## 🎯 Purpose
This project was built to strengthen understanding of core Python and OOP concepts such as:
- Classes and Objects
- Methods and `self`
- Lists and Dictionaries
- Loops and conditionals
- Flag variables
- Data management without databases

## 🐍 Python Version
Python 3.x

## 📋 Features
- **Insert Books** — Add new books or increase copies if book already exists
- **Delete Books** — Decrease copies or remove book completely when last copy is deleted
- **Search Books** — Find a book by title (case-insensitive)
- **Display All Books** — View all books currently in the library
- **Statistics** — View unique book count, total copies, and books per author
- Uses a 10×10 grid structure to store books
- Reuses deleted slots efficiently

## 🚀 How to Run

Open `library_management.ipynb` in Jupyter Notebook or VS Code and run all cells.

## 🗂️ Project Structure
library_management.ipynb - Main notebook containing the Library class and menu
README.md - Project documentation
LICENSE - License file
.gitignore - Ignored files configuration

## 💡 Concepts Used
| Concept | Where Used |
|---|---|
| Class & Object | `Library` class |
| Lists | `self.books` to store all books |
| Dictionaries | Each book stored as a dictionary |
| Flag variable | `found` flag in `delete` and `search` |
| Nested loops | Filling `None` slots in `insert` |
