you'll see function definitions that look like this:

"""
def a(x):
   '''
   x: int or float.
   '''
   return x + 1
"""

What are those three lines between def a(x): and return x + 1? These lines are called the docstring of the function. A docstring is a special type of comment that is used to document what your function is doing. Typically, docstrings will explain what the function expects the type(s) of the argument(s) to be, and what the function is returning.
In Python, docstrings appear immediately after the def line of a function, before the body. Docstrings start and end with triple quotes - this can be triple single quotes or triple double quotes, it doesn't matter as long as they match. To sum up this general form:
def myFunction(argument):
   """
   Docstring goes here. Explain what type argument(s) should have, and what your function
   is going to return.
   """
   < Code for your function (the body of the function) goes here >
   
As you begin coding your own functions, we strongly encourage you to document all your functions by using properly-formatted docstrings!
