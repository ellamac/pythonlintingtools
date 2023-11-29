# pythonlintingtools

Linting is the process of checking source code's quality, formatting and good programming practices using automatic tools, instead of manual
code reviewing and fixing.

Your task is to fix the below Python code, which uses bad programming practices. Remember that each programming language has its own rules for
code formatting, naming conventions, variable casing, etc.

Answer the following questions:

1. Investigate the code and attempt to find issues with it. Is it good Python code, and if not, why?
   As a reference, you can compare the code to Python's style guide at https://peps.python.org/pep-0008/

2. Install Flake8 as your Python linter using "pip install". Then, run the linter against the code. What warnings and errors do you get?

3. Investigate tools like "AutoPEP8" and "Black". What are they? Attempt to use either tool to automatically fix the bad code.
   Then run Flake8 again. Did you fix everything?

---

BadPythonCode.py:

`import os, sys

class exampleClass:
def **init**(self,val1,val2):
self.val1=val1
self.val2=val2

    def add(self):
        sum = self.val1+self.val2
        print("Sum is:", sum)

def another_function():
print("This function does nothing useful")

example = exampleClass(5, 10)
example.add()

for i in range(0,10):
print(i)

def unused_function():
pass

# Badly formatted dictionary

example_dict= { 'key1':'value1','key2':'value2','key3':'value3' }

# Unused imports

import random
import json

# Too many blank lines

# Unused variables

unused_var = 123

def yet_another_function():

# Inconsistent indentation

if True:
print("This block has inconsistent indentation")

def function_with_too_many_arguments(a, b, c, d, e, f, g, h, i, j, k):
pass

if **name**=="**main**":
another_function()
unused_function()
yet_another_function()
function_with_too_many_arguments(1,2,3,4,5,6,7,8,9,10,11)`
