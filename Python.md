<img src="https://github.com/abhayanigam/Learn_Python/blob/main/Assets/python.png" align="right" width="200" align="right" >

# Python CheatSheet
#### For In depth Knowledge [Click here.](https://github.com/abhayanigam/Learn_Python)

## Basics

Basic syntax from the python programming language

### Showing Output To User

the print function is used to display or print output

<div class="code-toolbar">

    print("Content that you wanna print on screen")

</div>

### Taking Input From User

the input function is used to take input from the user

<div class="code-toolbar">

    var1 = input("Enter your name: ")

</div>

### Empty List

This method allows you to create an empty list

<div class="code-toolbar">

    my_list = []

</div>

### Empty Dictionary

By putting two curly braces, you can create a blank dictionary

<div class="code-toolbar">

    my_dict = {}

</div>

### Range Function

range function returns a sequence of numbers, eg, numbers starting from 0 to n-1 for range(0, n)

<div class="code-toolbar">

    range(int_value)

</div>

## Comments

Comments are used to make the code more understandable for programmers, and they are not executed by compiler or interpreter.

### Single line comment

<div class="code-toolbar">

    #This is a single line comment

</div>

### Multi-line comment

<div class="code-toolbar">

    '''This is a
        multi-line
        comment'''

</div>

## Escape Sequence

An escape sequence is a sequence of characters; it doesn't represent itself when used inside string literal or character.

### Newline

Newline Character

<div class="code-toolbar">

    \n

</div>

### Backslash

It adds a backslash

<div class="code-toolbar">

    \\

</div>

### Single Quote

It adds a single quotation mark

<div class="code-toolbar">

    \'

</div>

### Tab

It gives a tab space

<div class="code-toolbar">

    \t

</div>

### Backspace

It adds a backspace

<div class="code-toolbar">

    \b

</div>

### Octal value

It represents the value of an octal number

<div class="code-toolbar">

    \ooo

</div>

### Hex value

It represents the value of a hex number

<div class="code-toolbar">

    \xhh

</div>

### Carriage Return

Carriage return or \r is a unique feature of Python. \r will just work as you have shifted your cursor to the beginning of the string or line.

<div class="code-toolbar">

    \r

</div>

## Strings

Python string is a sequence of characters, and each character can be individually accessed. Using its index.

### String

You can create Strings by enclosing text in both forms of quotes - single quotes or double-quotes.

<div class="code-toolbar">

    variable_name = "String Data"

</div>

### Slicing

Slicing refers to obtaining a sub-string from the given string.

<div class="code-toolbar">

    var_name[n : m]

</div>

### String Methods isalnum() method

Returns True if all characters in the string are alphanumeric

<div class="code-toolbar">

    string_variable.isalnum()

</div>

### isalpha() method

Returns True if all characters in the string are alphabet

<div class="code-toolbar">

    string_variable.isalpha()

</div>

### isdecimal() method

Returns True if all characters in the string are decimals

<div class="code-toolbar">

    string_variable.isdecimal()

</div>

### isdigit() method

Returns True if all characters in the string are digits

<div class="code-toolbar">

    string_variable.isdigit()

</div>

### islower() method

Returns True if all characters in the string are lower case

<div class="code-toolbar">

    string_variable.islower()

</div>

### isspace() method

Returns True if all characters in the string are whitespaces

<div class="code-toolbar">

    string_variable.isspace()

</div>

### isupper() method

Returns True if all characters in the string are upper case

<div class="code-toolbar">

    string_variable.isupper()

</div>

### lower() method

Converts a string into lower case

<div class="code-toolbar">

    string_variable.lower()

</div>

### upper() method

Converts a string into upper case

<div class="code-toolbar">

    string_variable.upper()

</div>

### strip() method

It removes leading and trailing spaces in the string

<div class="code-toolbar">

    string_variable.strip()

</div>

## List

A List in Python represents a list of comma-separated values of any data type between square brackets.

### List

<div class="code-toolbar">

    var_name = [element1, element2, and so on]

</div>

### List Methods index method

Returns the index of the first element with the specified value

<div class="code-toolbar">

    list.index(element)

</div>

### append method

Adds an element at the end of the list

<div class="code-toolbar">

    list.append(element)

</div>

### extend method

Add the elements of a list (or any iterable) to the end of the current list

<div class="code-toolbar">

    list.extend(iterable)

</div>

### insert method

Adds an element at the specified position

<div class="code-toolbar">

    list.insert(position, element)

</div>

### pop method

Removes the element at the specified position and returns it

<div class="code-toolbar">

    list.pop(position)

</div>

### remove method

The remove( ) method removes the first occurrence of a given item from the list

<div class="code-toolbar">

    list.remove(element)

</div>

### clear method

Removes all the elements from the list

<div class="code-toolbar">

    list.clear()

</div>

### count method

Returns the number of elements with the specified value

<div class="code-toolbar">

    list.count(value)

</div>

### reverse method

Reverse the order of the list

<div class="code-toolbar">

    list.reverse()

</div>

### sort method

Sorts the list

<div class="code-toolbar">

    list.sort(reverse=True|False)

</div>

</div>

<app-adsense adtype="ad" _nghost-serverapp-c29=""></app-adsense></div>

<div>

<div>

## Tuples

Tuples are represented as a list of comma-separated values of any data type within parentheses.

### Tuple Creation

<div class="code-toolbar">

    variable_name = (element1, element2, ...)

</div>

### Tuple Methods count method

It returns the number of times a specified value occurs in a tuple

<div class="code-toolbar">

    tuple.count(value)

</div>

### index method

It searches the tuple for a specified value and returns the position.

<div class="code-toolbar">

    tuple.index(value)

</div>

## Sets

A set is a collection of multiple values which is both unordered and unindexed. It is written in curly brackets.

### Set Creation: Way 1

<div class="code-toolbar">

    var_name = {element1, element2, ...}

</div>

### Set Creation: Way 2

<div class="code-toolbar">

    var_name = set([element1, element2, ...])

</div>

### Set Methods: add() method

Adds an element to a set

<div class="code-toolbar">

    set.add(element)

</div>

### clear() method

Remove all elements from a set

<div class="code-toolbar">

    set.clear()

</div>

### discard() method

Removes the specified item from the set

<div class="code-toolbar">

    set.discard(value)

</div>

### intersection() method

Returns intersection of two or more sets

<div class="code-toolbar">

    set.intersection(set1, set2 ... etc)

</div>

### issubset() method

Checks if a Set is Subset of Another Set

<div class="code-toolbar">

    set.issubset(set)

</div>

### pop() method

Removes an element from the set

<div class="code-toolbar">

    set.pop()

</div>

### remove() method

Removes the specified element from the Set

<div class="code-toolbar">

    set.remove(item)

</div>

### union() method

Returns the union of Sets

<div class="code-toolbar">

    set.union(set1, set2...)

</div>

## Dictionaries

The dictionary is an unordered set of comma-separated key: value pairs, within {}, with the requirement that within a dictionary, no two keys can be the same.

### Dictionary

<div class="code-toolbar">

    <dictionary-name> = {<key>: value, <key>: value ...}

</div>

### Adding Element to a dictionary

By this method, one can add new elements to the dictionary

<div class="code-toolbar">

    <dictionary>[<key>] = <value>

</div>

### Updating Element in a dictionary

If the specified key already exists, then its value will get updated

<div class="code-toolbar">

    <dictionary>[<key>] = <value>

</div>

### Deleting Element from a dictionary

del let to delete specified key: value pair from the dictionary

<div class="code-toolbar">

    del <dictionary>[<key>]

</div>

### Dictionary Functions & Methods len() method

It returns the length of the dictionary, i.e., the count of elements (key: value pairs) in the dictionary

<div class="code-toolbar">

    len(dictionary)

</div>

### clear() method

Removes all the elements from the dictionary

<div class="code-toolbar">

    dictionary.clear()

</div>

### get() method

Returns the value of the specified key

<div class="code-toolbar">

    dictionary.get(keyname)

</div>

### items() method

Returns a list containing a tuple for each key-value pair

<div class="code-toolbar">

    dictionary.items()

</div>

### keys() method

Returns a list containing the dictionary's keys

<div class="code-toolbar">

    dictionary.keys()

</div>

### values() method

Returns a list of all the values in the dictionary

<div class="code-toolbar">

    dictionary.values()

</div>

### update() method

Updates the dictionary with the specified key-value pairs

<div class="code-toolbar">

    dictionary.update(iterable)

</div>

## Conditional Statements

The if statements are the conditional statements in Python, and these implement selection constructs (decision constructs).

### if Statement

<div class="code-toolbar">

    if(conditional expression):
                    statements

</div>

### if-else Statement

<div class="code-toolbar">

    if(conditional expression):
        statements
    else:
        statements

</div>

### if-elif Statement

<div class="code-toolbar">

    if (conditional expression) :
        statements
    elif (conditional expression) :
        statements
    else :
        statements

</div>

### Nested if-else Statement

<div class="code-toolbar">

    if (conditional expression):
        if (conditional expression):
            statements
        else:
            statements
    else:
        statements

</div>

## Iterative Statements

An iteration statement, or loop, repeatedly executes a statement, known as the loop body, until the controlling expression is false (0).

### For Loop

The for loop of Python is designed to process the items of any sequence, such as a list or a string, one by one.

<div class="code-toolbar">

    for <variable> in <sequence>:
        statements_to_repeat

</div>

### While Loop

A while loop is a conditional loop that will repeat the instructions within itself as long as a conditional remains true.

<div class="code-toolbar">

    while <logical-expression> :
        loop-body

</div>

### Break Statement

The break statement enables a program to skip over a part of the code. A break statement terminates the very loop it lies within.

<div class="code-toolbar">

    for <var> in <sequence> :
        statement1
        if <condition> :
            break
            statement2
    statement_after_loop

</div>

### Continue Statement

The continue statement skips the rest of the loop statements and causes the next iteration to occur.

<div class="code-toolbar">

    for <var> in <sequence> :
        statement1
        if <condition> :
            continue
            statement2
            statement3
            statement4

</div>

## Functions

A function is a block of code that performs a specific task. You can pass parameters into a function. It helps us to make our code more organized and manageable.

### Function Definition

<div class="code-toolbar">

    def my_function(parameters):
        # Statements

</div>

## File Handling

File handling refers to reading or writing data from files. Python provides some functions that allow us to manipulate data in the files.

### open() function

<div class="code-toolbar">

    var_name = open("file name", "opening mode")

</div>

### close() function

<div class="code-toolbar">

    var_name.close()

</div>

### Read () function

The read functions contains different methods, read(),readline() and readlines()

<div class="code-toolbar">

    read() #return one big string

</div>

It returns a list of lines

<div class="code-toolbar">

    read-lines

</div>

It returns one line at a time

<div class="code-toolbar">

    readline

</div>

### Write () function

This function writes a sequence of strings to the file.

<div class="code-toolbar">

    write () #Used to write a fixed sequence of characters to a file

</div>

It is used to write a list of strings

<div class="code-toolbar">

    writelines()

</div>

### Append () function

The append function is used to append to the file instead of overwriting it. To append to an existing file, simply open the file in append mode (a):

<div class="code-toolbar">

    file = open("Hello.txt", "a")

</div>

## Exception Handling

An exception is an unusual condition that results in an interruption in the flow of the program.

### try and except

A basic try-catch block in python. When the try block throws an error, the control goes to the except block.

<div class="code-toolbar">

    try:
        [Statement body block]
        raise Exception()
    except Exception as e:
        [Error processing block]

</div>

## OOPS

It is a programming approach that primarily focuses on using objects and classes. The objects can be any real-world entities.

### class

The syntax for writing a class in python

<div class="code-toolbar">

    class class_name:
        #Statements

</div>

### class with a constructor

The syntax for writing a class with the constructor in python

<div class="code-toolbar">

    class Solution:

    # Default constructor
    def __init__(self):
    self.name = "Solution"

    # A method for printing dmembers
    def print_me(self):
    print(self.name)

</div>

### object

Instantiating an object

<div class="code-toolbar">

    <object-name> = <class-name>(<arguments>)

</div>

### filter function

The filter function allows you to process an iterable and extract those items that satisfy a given condition

<div class="code-toolbar">

    filter(function, iterable)

</div>

### issubclass function

Used to find whether a class is a subclass of a given class (classinfo) or not

<div class="code-toolbar">

    issubclass(class, classinfo)

</div>

## Iterators and Generators

Here are some of the advanced topics of the Python programming language like iterators and generators

### Iterator

Used to create an iterator over an iterable

<div class="code-toolbar">

    iter_list = iter(['Ramu', 'Aakash', 'Rohan']) 
    print(next(iter_list)) 
    print(next(iter_list)) 
    print(next(iter_list))

</div>

### Generator

Used to generate values on the fly

<div class="code-toolbar">

    # A simple generator function
    def my_gen():
    n = 1
    print('This is printed first')
    # Generator function contayield statements
    yield n
    n += 1
    print('This is printed second')
    yield n
    n += 1
    print('This is printed at last')
    yield n

</div>

## Decorators

Decorators are used to modifying the behavior of function or class. They are usually called before the definition of a function you want to decorate.

### property Decorator (getter)

<div class="code-toolbar">

    @property
    def name(self):
    return self.__name

</div>

### setter Decorator

It is used to set the property 'name'

<div class="code-toolbar">

    @name.setter
    def name(self, value):
    self.__name=value

</div>

### Deletor Decorator

It is used to delete the property 'name'

<div class="code-toolbar">

    @name.deleter #property-name.deleter decorator
    def name(self, value):
    print('Deleting..')
    del self.__name

</div>
