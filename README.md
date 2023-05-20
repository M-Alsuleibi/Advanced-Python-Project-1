# Advanced-Python-Project-1

This project consists of three questions in three different areas, take your time to read
and solve it. You are requested to submit a jupyter notebook file.
Question 1:
There is no doubt that decorators are important pattern and most of python developers
use them, either predefined or customly implemented. We talked about many real life
examples and two of them were cache and timing. Regarding timing we used it to
measure the runtime for each decorated function. So you are requested to:
a- Use the timing decorator to measure the running time for the following function:

def waste_some_time(num_times):
for _ in range(num_times):
sum([i**2 for i in range(10000)])

Try to run it with different test cases. There is a ready module in python which is timeit
module and this module can be used to measure the runtime.

timeit — Measure execution time of small code snippets
Source code: Lib/timeit.py This module provides a simple way to
time small bits of Python code. It has both a Command-Line
Interface as well as a callable one. It avoids a number of common
https://docs.python.org/3/library/timeit.html

b- You are requested to use this module to measure the runtime for the first function, try
to read and apply and compare the results of using the decorator and the module.
c- Briefly, is there any difference between timing decorator and this module?

Advanced Python Project 1 2
Question 2: (OOP)
In OOP we have instance methods, class methods and static methods, you are
requested two things:
a- Briefly, What are static methods and class methods?
b- Try to search and check how can we implement these. Implement any simple class
you want and apply three types of methods, implement one instance, static and
class methods and run them as well. submit a code which holds implementation
example of the. You can refer here also

Built-in Functions
The Python interpreter has a number of functions and types built
into it that are always available. They are listed here in alphabetical
order.,,,, Built-in Functions,,, A, abs(), aiter(), all(), a...
https://docs.python.org/3/library/functions.html#classmethod

Question3: Functions
Write a python function that takes a string consisting of both capital and lower letters
(Upper and Lower letters should be counted the same - better to normalize the text),
then you are requested to find the first non repeat character.
Example:
input: ‘Name naMag’
output: ‘e’
