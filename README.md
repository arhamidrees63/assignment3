# Assignment 3 – Command-Line Calculator

## 📌 Overview
This project is a Python command-line calculator with a REPL (Read–Eval–Print Loop) interface.  
It supports **addition, subtraction, multiplication, and division** with input validation and error handling.  
The project is fully tested with **pytest** and achieves **100% coverage**.  

---

## ⚙️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone git@github.com:arhamidrees63/assignment3_is601.git
   cd assignment3_is601

2. Create and activate a virtual environment:

python3 -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate.bat  # Windows

3. Install dependencies:

pip install -r requirements.txt

4. Run the calculator REPL:

python -m app.calculator

5. Example session:

Welcome to the calculator REPL! Type 'exit' to quit
Enter an operation (add, subtract, multiply, divide) and two numbers, or 'exit' to quit: add 2 3
Result: 5.0
Enter an operation... : divide 10 0
Division by zero is not allowed.
Enter an operation... : exit
Exiting calculator..

6. Run all tests:

pytest


7. Run tests with coverage:

pytest --cov=app --cov-report=term-missing --cov-report=html


8. Open the HTML coverage report:

open htmlcov/index.html   # macOS/Linux
start htmlcov/index.html  # Windows