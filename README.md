python is a popular programming language. It was created by Guido van Rossum, and released in 1991.

It is used for:

web development (server-side),
software development,
mathematics,
system scripting.
What can Python do?
Python can be used on a server to create web applications.
Python can be used alongside software to create workflows.
Python can connect to database systems. It can also read and modify files.
Python can be used to handle big data and perform complex mathematics.
Python can be used for rapid prototyping, or for production-ready software development.
Why Python?
Python works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc).
Python has a simple syntax similar to the English language.
Python has syntax that allows developers to write programs with fewer lines than some other programming languages.
Python runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.
Python can be treated in a procedural way, an object-oriented way or a functional way.
Good to know
The most recent major version of Python is Python 3, which we shall be using in this tutorial. However, Python 2, although not being updated with anything other than security updates, is still quite popular.
In this tutorial Python will be written in a text editor. It is possible to write Python in an Integrated Development Environment, such as Thonny, Pycharm, Netbeans or Eclipse which are particularly useful when managing larger collections of Python files.
Python Syntax compared to other programming languages
Python was designed for readability, and has some similarities to the English language with influence from mathematics.
Python uses new lines to complete a command, as opposed to other programming languages which often use semicolons or parentheses.
Python relies on indentation, using whitespace, to define scope; such as the scope of loops, functions and classes. Other programming languages often use curly-
brackets for this purpose

  # some basis operations in python #
"""
 2 + 3
5
>>> 2/3
0.6666666666666666
>>> 3//2
1
>>> 5%2
1
>>> 5//2
2
>>> 5*5*5
125
>>> 5**3
125
>>> print('c:\docs\navin')
<stdin>:1: SyntaxWarning: invalid escape sequence '\d'
c:\docs
avin
>>> print('naveen')
naveen
>>> print(naveen's phone')
  File "<stdin>", line 1
    print(naveen's phone')
                ^^^^^^^^^
SyntaxError: invalid syntax
>>> print("naveen's phone")
naveen's phone
>>> print('naveen "phone"')
naveen "phone"
>>> print('naveen\'s "phone"')
naveen's "phone"
>>> 10*naveen
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'naveen' is not defined
>>> 10*'naveen'
'naveennaveennaveennaveennaveennaveennaveennaveennaveennaveen'
>>>
"""
#variables and strings#
""""
n this lecture we are discussing variable in python:
Variable: It is a container where we can put our value
e.g 
 x=2 #here x is variable and 2 is value
 x+3
 5
y=3

Note:If I want to use output of previous operation so we use underscore (_) 
 _+y
8  # previous output 5 and y is 3 

Use String as a variable:
-- Strings in python are surrounded by either single quotation marks, or double quotation marks.
-- e.g  "shiva" ,'shiva'

Assign String to a Variable:
-- Assigning a string to a variable is done with the variable name followed by an equal sign and the string:
name='shiva'
name
shiva

Slicing String:
we can return a range of characters by using the slice syntax.
Specify the start index and the end index, separated by a colon, to return a part of the string.

-- Get the characters from position 2 to position 5 (not included):
name='youtube'
name[2:5]
 'utu'

Slice From the Start:
name[:5] #from starting to index 5 (exclude)
 'youtu'

Slice To the End:
name[2:] #from 2nd index to end
 'utube'

Negative Indexing:

0    1   2   3    4   5   6   #positive indexing
y    o   u   t    u   b   e
-7  -6  -5  -4   -3  -2  -1   #Negative indexing 

name[-1]
'e'

 name[:-1]
 'youtub'
name[:]
 'youtube'
 name [:0]
''
name[-5:-2]
'utu' 

Concatenate String:
 name+ ' telusko'
 'youtube telusko'
"""
#list and datatypes #
"""
Code

Python 3.7.3 (v3.7.3:ef4ec6ed12, Mar 25 2019, 22:22:05) [MSC v.1916 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> num = 2.5
>>> type(num)
<class 'float'>
>>> num = 5
>>> type(num)
<class 'int'>
>>> num = 6+9j
>>> type(num)
<class 'complex'>
>>> a = 5.6
>>> b = int(a)
>>> type(b)
<class 'int'>
>>> b
5
>>> k = float(b)
>>> k
5.0
>>> k = 6
>>> c = complex(b,k)
>>> c
(5+6j)
>>> b<k
True
>>> boll = b < k
>>> bool
<class 'bool'>
>>> b > k
False
>>> int(True)
1
>>> int(False)
0
>>> 1st = [25,36,45,12]
SyntaxError: invalid syntax
>>> lst = [25,36,45,12]
>>> type(lst)
<class 'list'>
>>> s = {25,36,45,15,12,25}
>>> s
{36, 12, 45, 15, 25}
>>> type(s)
<class 'set'>
>>> t = (25,36,4,57,12)
>>> type(t)
<class 'tuple'>
>>> str = "navin"
>>> st = 'a'
>>> type(st)
<class 'str'>
>>> range(10)
range(0, 10)
>>> list(range(10))
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
>>> list(range(2,10,2))
[2, 4, 6, 8]
>>> type(range(10))
<class 'range'>
>>> d = {'navin':'samsung','rahul':'Iphone','kiran':'Oneplus'}
>>> d
{'navin': 'samsung', 'rahul': 'Iphone', 'kiran': 'Oneplus'}
>>> d.keys()
dict_keys(['navin', 'rahul', 'kiran'])
>>> d.values()
dict_values(['samsung', 'Iphone', 'Oneplus'])
>>> d['rahul']
'Iphone'
>>> d.get('kiran')
'Oneplus'
>>>
"""
#methos in python #
"""
>>> num = [10,20,30,40,50]
>>> num = [10,20,30,40,50,45]
>>> num.sort
<built-in method sort of list object at 0x000001A5DD68D180>
>>> num.sort()
>>> num
[10, 20, 30, 40, 45, 50]
>>> num.append(25)
>>> num
[10, 20, 30, 40, 45, 50, 25]
>>> num.insert(3,75)
>>> num
[10, 20, 30, 75, 40, 45, 50, 25]
>>> num.remove(50)
>>> num
[10, 20, 30, 75, 40, 45, 25]
>>> num.pop(3)
75
>>> num
[10, 20, 30, 40, 45, 25]
>>> num.del(2:)
  File "<stdin>", line 1
    num.del(2:)
        ^^^
SyntaxError: invalid syntax
>>> num.del([2:])
  File "<stdin>", line 1
    num.del([2:])
        ^^^
SyntaxError: invalid syntax
>>> del num(2:)
  File "<stdin>", line 1
    del num(2:)
             ^
SyntaxError: invalid syntax
>>> del num[2:]
>>> num
[10, 20]
>>> num.extend([12,35,34]0
  File "<stdin>", line 1
    num.extend([12,35,34]0
               ^^^^^^^^^^^
SyntaxError: invalid syntax. Perhaps you forgot a comma?
>>> num.extend([12,34,43])
>>> num
[10, 20, 12, 34, 43]
>>> min(num)
10
>>> max(num)
43
>>> sum(num)
119
>>> num.sort()
>>> num
[10, 12, 20, 34, 43]
>>>
#methos in python #
"""
>>> num = [10,20,30,40,50]
>>> num = [10,20,30,40,50,45]
>>> num.sort
<built-in method sort of list object at 0x000001A5DD68D180>
>>> num.sort()
>>> num
[10, 20, 30, 40, 45, 50]
>>> num.append(25)
>>> num
[10, 20, 30, 40, 45, 50, 25]
>>> num.insert(3,75)
>>> num
[10, 20, 30, 75, 40, 45, 50, 25]
>>> num.remove(50)
>>> num
[10, 20, 30, 75, 40, 45, 25]
>>> num.pop(3)
75
>>> num
[10, 20, 30, 40, 45, 25]
>>> num.del(2:)
  File "<stdin>", line 1
    num.del(2:)
        ^^^
SyntaxError: invalid syntax
>>> num.del([2:])
  File "<stdin>", line 1
    num.del([2:])
        ^^^
SyntaxError: invalid syntax
>>> del num(2:)
  File "<stdin>", line 1
    del num(2:)
             ^
SyntaxError: invalid syntax
>>> del num[2:]
>>> num
[10, 20]
>>> num.extend([12,35,34]0
  File "<stdin>", line 1
    num.extend([12,35,34]0
               ^^^^^^^^^^^
SyntaxError: invalid syntax. Perhaps you forgot a comma?
>>> num.extend([12,34,43])
>>> num
[10, 20, 12, 34, 43]
>>> min(num)
10
>>> max(num)
43
>>> sum(num)
119
>>> num.sort()
>>> num
[10, 12, 20, 34, 43]
>>>
"""
#tuple and set#
"""
>>>
>>> tup = (10,20,30,40)
>>> tup
(10, 20, 30, 40)
>>> tup[1]
20
>>> tup.insert[30]
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
AttributeError: 'tuple' object has no attribute 'insert'
>>> tup.count
<built-in method count of tuple object at 0x000001A5DD999BC0>
>>> tup
(10, 20, 30, 40)
>>> tup.index
<built-in method index of tuple object at 0x000001A5DD999BC0>
>>>
>>>
>>> s = {10,45,34,20,98}
>>> s
{34, 98, 20, 10, 45}
>>> s
{34, 98, 20, 10, 45}
>>> s = {10,45,23,46,23}
>>> s
{10, 45, 46, 23}
>>> s.add(20)
>>> s
{10, 45, 46, 20, 23}
>>> s.remove(46)
>>> s
{10, 45, 20, 23}
>>>
"""
