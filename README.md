# IT-Automation-Python






# Basics-Python
Please check off the following topics to confirm that you already understand them! You're only expected to understand the basics of how to manipulate them—details about usage will be explained later if needed. If anything looks unfamiliar, you can check out one of the[introductory Python classes](https://www.udacity.com/course/programming-foundations-with-python--ud036). This course will also default to [Python 2](https://docs.python.org/2/) where applicable, though it's very similar to [Python 3](https://docs.python.org/3/)!

### Comments

    # This is a one-line Python comment - code blocks are so useful!
    """This type of comment is used to document the purpose of functions and classes."""

### Declaration/Initialization

    # Remember values, not variables, have data types.
    # A variable can be reassigned to contain a different data type.
    answer = 42
    answer = "The answer is 42."

### Data Types

    boolean = True
    number = 1.1
    string = "Strings can be declared with single or double quotes."
    list = ["Lists can have", 1, 2, 3, 4, "or more types together!"]
    tuple = ("Tuples", "can have", "more than", 2, "elements!")
    dictionary = {'one': 1, 'two': 2, 'three': 3}
    variable_with_zero_data = None

### Simple Logging

    print "Printed!"

### Conditionals

    if cake == "delicious":
        return "Yes please!"
    elif cake == "okay":
        return "I'll have a small piece."
    else:
        return "No, thank you."

### Loops

    for item in list:
        print item

    while (total < max_val):
        total += values[i]
        i += 2

### Functions

    def divide(dividend, divisor):
        quotient = dividend / divisor
        remainder = dividend % divisor
        return quotient, remainder

    def calculate_stuff(x, y):
        (q, r) = divide(x,y)
        print q, r

### Classes

    class Person(object):
      def __init__(self, name, age):
          self.name = name
          self.age = age 

      def birthday(self):
          self.age += 1
