# Custom_Compiler
Compiler created in Python3 to read a custom programming language.

## Program Grammar:
![image](https://github.com/RomanSaddiJr/Custom_Compiler/assets/105825537/e1865c24-5d70-41fb-9cd0-d1b38de5000c)

## Example Program:
![image](https://github.com/RomanSaddiJr/Custom_Compiler/assets/105825537/d14a1544-c631-44af-be9d-3ca372813590)
## Output:
![image](https://github.com/RomanSaddiJr/Custom_Compiler/assets/105825537/8ef07d60-e559-4d73-8c88-20b451310fc9)

# How It's Made:

**Tools used:** Python3

This custom compiler, developed using Python 3, showcases the power and versatility of the language in building sophisticated language processing tools. By leveraging the expressive features and extensive libraries available in Python, this compiler seamlessly translates and interprets code written in a custom language.In addition to the core functionalities, the compiler incorporates error handling mechanisms.

## Contents:
This repository contains the files:

**'requirements.txt':**
This files contains the necessary libraries to be installed.

**'src -> main.py':** driver code of the program

**'src -> settingUp.py':** removes comments and unecessary lines for grammar checking.

**'src -> create_table.py':** creates the predictive parsing table

**'src -> grammar.py':** reads the programming language input file and runs it through a predictive parsing table for grammar checking.

**'src -> check_arithmetic.py':** checks the arithmetic in the programming language input file. 

**'src -> errors.py':** performs error checking and gives error handling messages.

**'src -> convertPython.py':** assuming the program input file grammar is valid and no errors were found, converts the language into python3.

**'src -> output.py':** the output python file

**'src -> finalp1.txt':** the custom program 

**'src -> finalp2.txt':** the custom program after running "settingUp.py"

**'src -> math.txt':** the math found in the custom program

**'src -> parsing_table.txt':** the predictive parsing table that is created from create_table.py

# How to run:
First, write your custom program using the given grammar into the file "finalp1.txt". Then, simply run "main.py" and follow the instructions on the console.








