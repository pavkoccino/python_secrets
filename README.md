# Python things to remember
### This readme file is my takeaway from all the learning materials I've been through. I don't want to forget this knowledge.
- Try-except-else blocks, else block is the place where the code goes, if try block goes well. It is a good practice to put ONLY WHAT CAN CAUSE THE EXCEPTION to the try block and rest of the code to the else block.
- Modes for working with the files > r, r+, a, w...be careful, 'w' deletes the content of the file if it already exists!
- If I am generating a lot of numbers, definitely go with generators. This is much faster square = (i*i for i in irange(1000000)) than this square = [i*i for i in irange(1000000)].
- Oh yeah, list comprehensions are a must. Try to use it whenever you need to generate a list.
- Define the functions saying what type is expected for an argument, also add return type. It just looks good and makes code more readable for others.
- Use snake_case instead of camelCase.
- If you write except ValueError, the except block will only handle ValueErrors that occur in try block. It would not handle for example file not found error.
- Python allows multiple inheritance.
- Write tests for code's critical behaviros and then aim for the full coverage only if the project has a widespread use.


### What I need to learn
- Abstact classes.
- stub files (.pyi).
- get back to **kwargs.

### Modules I used in my life
- import json
- import timeit
- import os
- import jira
- import unittest
