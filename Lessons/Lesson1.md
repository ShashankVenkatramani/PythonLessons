# Python Basics Lesson 1

## Lesson Goal

The purpose of this lesson is to build an understanding as to how python works under the hood. While a thorough understanding of python is not necesary to get a running program, having an intuitive map of python internally helps understand the usage of libraries, environments, and many other aspects leveraged within python.

## Python Structure
### Syntax

Even though today's computers are able to execute highly advanced algorithms, ranging from protein fold simulations, to artificial intelligence, they are all based off of a collection of basic instructions. Unfortunately computers don't speak English, so writing instructions for your machine to understand is lengthy and inneffecient. Programming languages can be thought of as a middle man, where you can write instructions in English (with accordance to certain rules), and the programming language converts it into instructions your computer understands.

This process starts with you typing commands using the English alphabet. Even though it is in English, you must adhere to the instructions of the programming language, similar to how Spanish and English are different, so are Python and Java.

Here is an example with Python to print text:
```python
print("Hello there! Welcome to Python")
```
Here is an example with Java to print text:
```Java
System.out.println("Hello There! Welcome to Python")
```

As you can see both of Python and Java have different ways to write "Hello there! Welcome to Python"

The rules and code that you create when using any programming language is called syntax, and the syntax for each language is different, dependent upon how the developer made the programming language.

### Text Editor

One way to "write commands" or program is to create a file with the instructions in it. You then give this file of instructions to your computer to run. In order to create, and save these files you need a text editor. For Python and many other programming languages a normal text editor can be used, such as notepad, and textedit, however you can download text editors online that come with extra functionality. Once you get your text editor you can now write your "instructions" as syntax depending on which language you are writing in, in this case python. In order to denote which language you are writing your program in, you need to add a file extension when saving your program. In python's case you add a .py at the end of each file when you save as, so that the computer recognizes it as a python file.

### Python Compiling

After getting your text file with all your syntax saved on it, you now need to convert it from English into a language that computers can understand. In order to convert it into machine code (the language computers use) you use the Python Interpreter.

<details><summary>How does python interpreter work? (Extra details, optional to know)</summary>The python interpreter takes your program file and compiles (think of converting) it into bytecode by separating all of your syntax into their individual instructions and saving them as a list of tokens. These tokens are stored within a bytecode file (.pyc), and if any errors are encountered it interrupts the process. The byte code file then gets run by python virtual machine.


In order to use python's interpreter you must have python downloaded. Mac OS X comes with python pre installed, if you are windows however you need to install python from https://www.python.org/downloads/

### Lesson 2

In lesson 2 you will use your new knowledge to type and create your own program that prints to the console.  <br>

[Lesson 2](Lesson2.md)
