# 🐍  10DaysOfPython

- [🐍  10DaysOfPython](#--10daysofpython)
- [📘 Day 1](#-day-1)
  - [Welcome](#welcome)
  - [Introduction](#introduction)
  - [Why Python ?](#why-python-)
  - [Environment Setup](#environment-setup)
    - [Installing Python](#installing-python)
    - [Python Shell](#python-shell)
    - [Installing Visual Studio Code](#installing-visual-studio-code)
      - [How to use visual studio code](#how-to-use-visual-studio-code)
  - [Basic Python](#basic-python)
    - [Python Syntax](#python-syntax)
    - [Python Indentation](#python-indentation)
    - [Comments](#comments)
    - [Data types](#data-types)
      - [Number](#number)
      - [String](#string)
      - [Booleans](#booleans)
      - [List](#list)
      - [Dictionary](#dictionary)
      - [Tuple](#tuple)
      - [Set](#set)
    - [Checking Data types](#checking-data-types)
    - [Python File](#python-file)
  - [💻 Exercises - Day 1](#-exercises---day-1)
    - [Exercise: Level 1](#exercise-level-1)
    - [Exercise: Level 2](#exercise-level-2)
- [Day 2](#day-2)
  - [Builtin Functions](#builtin-functions)
  - [Variables](#variables)
- [Day 3](#day-3)
- [Day 4](#day-4)
- [Day 5](#day-5)
- [Day 6](#day-6)
- [Day 7](#day-7)
- [Day 8](#day-8)
- [Day 9](#day-9)
- [Day 10](#day-10)

|   # Day   | Topics                                                    |
|-----------|:--------------------------------------------------------------------------------------------------- |
|  01   |  [Introduction - Installing Python  - Writing Python Script  - Installing VScode  - Writing Python Scripts on VSCode](./readme.md)|
|  02 |  [Built-in Functions, Variables]()|
|  03 |  [Data types, type conversion, Operators]()|
|  04 |  [Strings]()|
|  05 |  [Modules]() |
|  06 |  [Conditionals]() |
|  07 |  [Lists]()|
|  08 |  [Loops]()|
|  09 |  [Sets,Tuples, Dictionaries]()|
| 10  |  [Functions, docstrings, Lambda Function, Higher Order Function]()|

# 📘 Day 1

## Welcome

**Congratulations** for deciding to participate in a _0 days of Python_ programming challenge . In this challenge you will learn the fundamental of Python and programming principles. In the end of the challenge you will get a _10DaysOfPython_ programming challenge certificate.

[Join the telegram channel to get help](https://t.me/ThirtyDaysOfPython)

## Introduction

Python is a high-level programming language for general-purpose programming. It is open source. This 10 days python challenge will help you learn the latest version of Python, Python 3 step by step. The topics are broken down into 10 days, where each day contains several topics with easy-to-understand explanations, real-world examples and many hands on exercises.

This challenge is designed for beginners and professionals who want to learn python programming language.

## Why Python ?

It is a programming language which is very close to human language and because of that it is easy to learn and easy to use.
Python is used by various industries and companies (including Google). It has been used to develop web applications, desktop applications, system adminstration, and machine learning libraries. Python is highly embraced language in the data science and machine learning community. I hope this is enough to convince you to start learning python. Python is eating the world and you are killing it before it eats you.

## Environment Setup

### Installing Python

To run a python script you need to install python. Let's [download](https://www.python.org/) python.
If your are a windows user. Click the yellow button.

[![installing on Windows](./images/installing_on_windows.png)](https://www.python.org/)

If you are a macOS user. Click on the latest Python 3 release link.

[![installing on Windows](./images/installing_on_macOS.png)](https://www.python.org/)

To check if python is installed write the following command on your device terminal.
If you are a Windows user, open the command prompt by writing cmd on the taskbar search field. Then a command prompt will be opened. 
![Python Version](./images/windows_command_prompt.png)

Write the following code and and press the enter key
```shell
python --version
```

![Python Version](./images/python_version_windows_cmd.png)


If you are a MacOs users, you open the terminal and write
```sh
asabeneh@Asabeneh:~$ python --version
Python 3.9.5
```


As you can see from the terminal, I am using _python 3.9.5_ version at the moment. If you mange to see the python version, well done. Python has been installed on your machine. Let us continue to the next section to write scripts on the Python Interactive shell.

### Python Shell

Python is an interpreted scripting language, so it doesn't need to be compiled. It means it executes the code line by line. Python comes with a _Python Shell (Python Interactive Shell)_. It is used to execute a single python command and get the result.

Python Shell waits for the python code from the user. When you enter the code, it interprets the code and shows the result in the next line.
Open your terminal or command prompt(cmd) and write:

```shell
python
```

![Python Scripting Shell](./images/opening_python_interactive_shell_windows.png)

The python interactive shell is opened and it is waiting for you to write python code. You will write your python script next to this symbol >>> and then press Enter key.
Let us write our very first script on the python scripting shell.

![Python script on python shell](./images/adding_on_python_shell.png)

Well done, you wrote your first python script on python interactive shell. How do we close this shell ?
To close the shell, next to this symbol >> write **exit()** command and press Enter.

![Exit from python shell](./images/exit_from_shell.png)

Now, you know how to open the python interactive shell and how to exit from it.

Python will give you results if you write scripts that python understands, if not it returns errors. Let's make a deliberate mistake and see what python will return.

![Invalid Syntax Error](./images/invalid_syntax_error.png)

As you can see from the returned error, python is so clever that it knows the mistake we made and which was _Syntax Error: invalid syntax_. Using x as multiplication in python is a syntax error because (x) is not a valid syntax in python. Instead of (**x**) we use asterisk (*) for multiplication. The returned error clearly shows what to fix.
The process of identifying and removing errors from a program is called *debugging*. Let's debug it by putting * in place of **x**.

![Fixing Syntax Error](./images/fixing_syntax_error.png)

Our bug was fixed, the code ran and we got a result we were expecting. As a programmer you will see such kind of errors on daily basis. It is good to know how to debug. To be good at debugging you should understand what kind of errors you are facing:SyntaxError, IndexError, ModuleNotFoundError, KeyError, ImportError etc. We will see more about different python **_error types_** in later sections.

Let's practice more how to use python interactive shell. Go to your terminal or command prompt and write the word **python**.

![Python Scripting Shell](./images/opening_python_shell.png)

The python interactive shell is opened. Let's do some basic mathematic operations (addition, subtraction, multiplication, division, modulus,  exponential).
Lets do some maths first before we write any python code:

- 2 + 3 = 5
- 3 - 2 = 1
- 3 \* 2 = 6
- 3 / 2 = 1.5
- 3 ^ 2 = 3 x 3 = 9

In python we have the following additional operations:

- 3 % 2 = 1 => which means finding the remainder
- 3 // 2 = 1 => which means removing the remainder

Lets change the above mathematical expressions to code. The python shell has been opened and lets write a comment at the very beginning of the shell.
A _comment_ is a part of the code which is not executed by python. So we can leave some text in our code to make our code more readable. Python does not run the comment part. A comment in python starts with hash(#) symbol.
This is how you write a comment in python

```shell
 # comment starts with hash
 # this is a python comment, because it starts with a (#) symbol
```

![Maths on python shell](./images/maths_on_python_shell.png)

Before we move on to the next section, lets practice more on the python interactive shell. Close the opened shell by writing _exit()_ on the shell and open it again and let's practice how to write text on the python shell.

![Writing String on python shell](./images/writing_string_on_shell.png)

### Installing Visual Studio Code

The python interactive shell is good to try and test small script codes but it won't be for a big project. In real work environment, developers use different code editors to write codes. In this 10 days of Python programming challenge we will use visual studio code. Visual studio code is a very popular open source text editor. I am a fan of vscode and I would recommend to [download](https://code.visualstudio.com/) visual studio code, but if you are in favor of other editors, feel free to follow with what you have.

[![Visual Studio Code](./images/vscode.png)](https://code.visualstudio.com/)

If you installed visual studio code, let's see how to use it.

#### How to use visual studio code

Open the visual studio code by double clicking the visual studio icon. When you open it you will get this kind of interface. Try to interact with the labeled icons.

![Visual studio Code](./images/vscode_ui.png)

Create a folder named 10DaysOfPython on your desktop. Then open it using visual studio code.

![Opening Project on Visual studio](./images/how_to_open_project_on_vscode.png)

![Opening a project](./images/opening_project.png)

After opening it you will see shortcuts for creating files and folders inside of 10DaysOfPython project's directory. As you can see below, I have created the very first file, helloworld.py. You can do the same.

![Creating a python file](./images/helloworld.png)

After a long day of coding, you want to close your code editor, right? This is how you will close the opened project.

![Closing project](./images/closing_opened_project.png)

Congratulations, you have finished setting up the development environment. Let's start coding.

## Basic Python

### Python Syntax

A python script can be written in python interactive shell or in the code editor. A python file has an extension .py.

### Python Indentation

An indentation is a white space in a text. Indentation in many languages is used to increase code readability, however python uses indentation to create block of codes. In other programming languages curly brackets are used to create blocks of codes instead of indentation. One of the common bugs when writing python code is wrong indentation.

![Indentation Error](./images/indentation.png)

### Comments

Comments are very important to make the code more readable and to leave remarks in our code. Python doesn't run comment parts of our code.
Any text starting with hash(#) in python is a comment.

**Example: Single Line Comment**

```shell
    # This is the first comment
    # This is the second comment
    # Python is eating the world
```

**Example: Multiline Comment**

Triple quote can be used for multiline comment if it is not assigned to a variable

```shell
"""This is multiline comment
multiline comment takes multiple lines.
python is eating the world
"""
```

### Data types

In python there are several types of data types. Let's get started with the most common ones. Different data types will be covered in detail in other sections. For the time being let us just go through the different data types and get familiar with them. You do not have to have a clear understanding now.

#### Number

- Integer: Integer(negative, zero and positive) numbers
    Example:
    ... -3, -2, -1, 0, 1, 2, 3 ...
- Float: Decimal number
    Example
    ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...
- Complex
    Example
    1 + j, 2 + 4j

#### String

A collection of one or more characters under a single or double quote. If a string is more than one sentence then we use a triple quote.

**Example:**

```py
'Asabeneh'
'Finland'
'Python'
'I love teaching'
'I hope you are enjoying the first day'
```

#### Booleans

A boolean data type is either a True or False value. T and F should be always uppercase.

**Example:**

```python
    True  #  Is the light on? If it is on, then the value is True
    False # Is the light on? If it is off, then the value is False
```

#### List

Python list is an ordered collection which allows to store different data type items. A list is similar to an array in JavaScript.

**Example:**

```py
[0, 1, 2, 3, 4, 5]  # all are the same data types - a list of numbers
['Banana', 'Orange', 'Mango', 'Avocado'] # all the same data types - a list of strings (fruits!)
['Finland','Estonia', 'Sweden','Norway'] # all the same data types - a list of strings (countries!)
['Banana', 10, False, 9.81] # different data types in the list - string, integer, boolean and float
```

#### Dictionary

A python dictionary object is an unordered collection of data in a key:value pair format. 

**Example:**

```py
{'name':'Asabeneh', 'country':'Finland', age:250, 'is_married':True}
```

#### Tuple

A tuple is an ordered collection of different data types like list but tuples can not be modified once they are created. They are immutable.

**Example:**

```py
('Asabeneh', 'Brook', 'Abraham', 'Lidiya')
```

#### Set

A set is a collection of data types similar to list and tuple. Unlike list and tuple, set is not an ordered collection of items. Like in mathematics, set in python stores only unique items.

In later sections, we will go in detail about each and every python data type.

**Example:**

```py
{3.14, 9.81, 2.7} # order is not important in set
```

### Checking Data types

In Python, there are many builtin functions that allows to do different operations. For instance, the *print()* function allows to print an output. The *input()* function allows to get user input. We will go in detail about builtin functions in the second day. 

To check the data type of certain data/variable we use the **type** builtin function. In the following terminal you will see different python data types:

![Checking Data types](./images/checking_data_types.png)

### Python File

First open your project folder, 30DaysOfPython. If you don't have this folder, create a folder name called 30DaysOfPython. Inside this folder, create a file called helloworld.py. Now, let's do what we did on python interactive shell using visual studio code.
The python interactive shell was printing without using **print** but on visual studio code to see our result we should use a built in function **print(some data to print)**. See the examples below.

**Example:**

The file name is helloworld.py

```py
# Day 1 - 30DaysOfPython Challenge

print(2 + 3)             # addition(+)
print(3 - 1)             # subtraction(-)
print(2 * 3)             # multiplication(*)
print(3 / 2)             # division(/)
print(3 ** 2)            # exponential(**)
print(3 % 2)             # modulus(%)
print(3 // 2)            # Floor division operator(//)

# Checking data types
print(type(10))          # Int
print(type(3.14))        # Float
print(type(1 + 3j))      # Complex number
print(type('Asabeneh'))  # String
print(type([1, 2, 3]))   # List
print(type({'name':'Asabeneh'})) # Dictionary
print(type({9.8, 3.14, 2.7}))    # Set
print(type((9.8, 3.14, 2.7)))    # Tuple
```

To run the python file check the image below. You can run the python file either by running the green button or by typing *python helloworld.py* in the terminal .

![Running python script](./images/running_python_script.png)

🌕  You are amazing. You have just completed day 1 challenge and you are on your way to greatness. Now do some exercises for your brain and for your muscle.

## 💻 Exercises - Day 1


### Exercise: Level 1

1. A rectangle has 10 m width and 20m height. Find the perimeter.
2. Open the command prompt or terminal and check the python version you are using
3. Write a single line comment that says I am enjoying 10DaysOfPython challenge
4. Write a multiline comment that has 4 lines
5. Open the python interactive shell and do the following operations. The operands are 9 and 5. Check the example above
   - addition(+)
   - subtraction(-)
   - multiplication(\*)
   - modulus(%)
   - division(/)
   - exponential(\*\*)
   - floor division operator(//)
6. Write strings on the python interactive shell. The strings are the following:
   - Your name
   - Your family name
   - Your country
   - I am enjoying 30 days of python
7. Check the data types of the following data:
   - 10
   - 9.8
   - 3.14
   - 4 - 4j
   - ['Asabeneh', 'Python', 'Finland']
   - Your name
   - Your family name
   - Your country

### Exercise: Level 2

1. Create a folder named day_1 inside 10DaysOfPython folder. Inside day_1 folder, create a python file helloworld.py and repeat questions 1, 2, 3 and 4. Remember to use _print()_ when you are working on a python file. Navigate to the directory where you have saved your file, and run it.

🎉 CONGRATULATIONS ! 🎉

# Day 2

## Builtin Functions

## Variables

# Day 3

# Day 4

# Day 5

# Day 6

# Day 7 

# Day 8

# Day 9

# Day 10