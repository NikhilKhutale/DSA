# Lesson 1: Overview of Python


## Objective

The objective of this lesson is to understand the basics of Python. We will explore its history, key features, and benefits. Additionally, we will cover the installation process across various operating systems, set up an IDE like VS Code, and write and run our first Python script.

## Introduction to Python

Python is a high-level, interpreted programming language known for its simplicity and versatility. Created by Guido van Rossum and first released in 1991, Python has become one of the most popular programming languages in the world. Its design philosophy based on code readability and simplicity, making it an ideal choice for beginners and experienced programmers alike. Python's syntax allows developers to express concepts in fewer lines of code compared to other languages, which contributes to its efficiency and ease of use.

## History and Evolution

Python's journey began in the late 1980s when Guido van Rossum, a Dutch programmer, started working on it as a successor to the ABC language. The first official release, Python 0.9.0, came out in February 1991, featuring classes with inheritance, exception handling, functions, and the core data types like list, dict, str, and more.

## Key Features and Benefits

Key Features and Benefits
Python is renowned for several key features that make it an attractive choice for a wide range of applications:

- **Readability and Simplicity**: Python's syntax is clear and concise, resembling plain English, which enhances readability and reduces the learning curve.
* **Versatility**: It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.
+ **Extensive Standard Library**: Python's standard library offers modules and packages for virtually every application, from web development to scientific computing.
- **Interpreted Language**: Python is an interpreted language, meaning code is executed line by line, which facilitates debugging and rapid development.
* **Dynamic Typing**: Variables in Python are dynamically typed, reducing the need for explicit declarations and simplifying code.
+ **Community Support**: Python boasts a large and active community, providing extensive resources, libraries, and frameworks to assist developers.

## Setting Up the Python Environment

To start coding in Python, you need to set up your environment by installing Python and choosing an appropriate integrated development environment (IDE).

### Installing Python

**Windows**
- **Download Python Installer**: Visit the official Python website and download the installer for Windows.
* **Run the Installer**: Execute the downloaded file and follow the installation wizard. Ensure you check the box to "Add Python to PATH" before proceeding.
+ **Verify Installation**: Open Command Prompt and type python --version to confirm that Python is installed correctly.

**macOS**

1. **Install Homebrew (if not already installed)**: Open Terminal and enter:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
2. **Install Python**: With Homebrew installed, type:
```
brew install python
```
3. **Verify Installation**: Check the installation by typing python3 --version in Terminal


**Linux**


1. **Update Package List**: Open your terminal and update your package list:
```
sudo apt update
```
2. **Install Python**: Enter the following command:
```
sudo apt install python3
```
3. **Verify Installation**: Confirm the installation by typing python3 --version.

## Setting Up IDEs
Choosing the right IDE can significantly enhance your productivity. Here are steps to set up three popular IDEs for Python development:

**Visual Studio Code (VS Code)**
1. **Download and Install**: Go to the [VS Code website](https://code.visualstudio.com/) and download the appropriate installer for your operating system.

2. **Install Python Extension**: Launch VS Code and install the Python extension by Microsoft from the Extensions marketplace.

3. **Configure Python Interpreter**: Open the Command Palette (Ctrl+Shift+P), type Python: Select Interpreter, and choose the correct Python version.

## Writing and Running Your First Python Script

Now that your environment is set up, it's time to write and run your first Python script.

1. **Open Your IDE**: Launch the IDE you have set up (PyCharm, VS Code, or Jupyter Notebook).

2. **Create a New File**: In your IDE, create a new file and name it hello.py.

3. **Write Your Script**: Enter the following code in your new file:
```
print("Hello, World!")
```
4. **Save and Run**: Save your file and run it. In PyCharm and VS Code, you can usually run your script by right-clicking on the file and selecting "Run". In Jupyter Notebook, simply create a new cell, enter the code, and press Shift+Enter to execute it.


Upon running your script, you should see the output "Hello, World!" This simple exercise demonstrates Python's straightforward syntax and ease of use.
