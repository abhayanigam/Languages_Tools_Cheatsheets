<img src="https://github.com/abhayanigam/Learn_C/blob/main/c.png" align="right" width="200" align="right" />

# C Language CheatSheet

## Basics

Basic syntax and functions from the C programming language.

### Boilerplate Code

<div class="code-toolbar">

    #include<stdio.h>
                int main()
                {
                return(0);
                }

</div>

</div>

### printf function

It is used to show output on the screen

<div class="code-toolbar">

    printf("Hello World!")

</div>

</div>

### scanf function

It is used to take input from the user

<div class="code-toolbar">

    scanf("placeholder", variables)

</div>

</div>

## Comments

A comment is the code that is not executed by the compiler, and the programmer uses it to keep track of the code.

### Single line comment

<div class="code-toolbar">

    // It's a single line comment

</div>

</div>

### Multi-line comment

<div class="code-toolbar">

    /* It's a 
                multi-line
                comment
                */

</div>

</div>

## Data types

The data type is the type of data

### Character type

Typically a single octet(one byte). It is an integer type

<div class="code-toolbar">

    char variable_name;

</div>

</div>

### Integer type

The most natural size of integer for the machine

<div class="code-toolbar">

    int variable_name;

</div>

</div>

### Float type

A single-precision floating-point value

<div class="code-toolbar">

    float variable_name;

</div>

</div>

### Double type

A double-precision floating-point value

<div class="code-toolbar">

    double variable_name;

</div>

</div>

### Void type

Represents the absence of the type

<div class="code-toolbar">

    void

</div>

</div>

</div>

<div>

<div>

## Escape Sequences

It is a sequence of characters starting with a backslash, and it doesn't represent itself when used inside string literal.

### Alarm or Beep

It produces a beep sound

<div class="code-toolbar">

    \a

</div>

</div>

### Backspace

It adds a backspace

<div class="code-toolbar">

    \b

</div>

</div>

### Form feed

<div class="code-toolbar">

    \f

</div>

</div>

### Newline

Newline Character

<div class="code-toolbar">

    \n

</div>

</div>

### Carriage return

<div class="code-toolbar">

    \r

</div>

</div>

### Tab

It gives a tab space

<div class="code-toolbar">

    \t

</div>

</div>

### Backslash

It adds a backslash

<div class="code-toolbar">

    \\

</div>

</div>

### Single quote

It adds a single quotation mark

<div class="code-toolbar">

    \'

</div>

</div>

### Question mark

It adds a question mark

<div class="code-toolbar">

    \?

</div>

</div>

### Octal No.

It represents the value of an octal number

<div class="code-toolbar">

    \nnn

</div>

</div>

### Hexadecimal No.

It represents the value of a hexadecimal number

<div class="code-toolbar">

    \xhh

</div>

</div>

### Null

The null character is usually used to terminate a string

<div class="code-toolbar">

    \0

</div>

</div>

## Conditional Instructions

Conditional statements are used to perform operations based on some condition.

### If Statement

<div class="code-toolbar">

    if (/* condition */)
                {
                /* code */
                }

</div>

</div>

### If-else Statement

<div class="code-toolbar">

    if (/* condition */)
                {
                /* code */
                }
                else{
                /* Code */
                }

</div>

</div>

### if else-if Statement

<div class="code-toolbar">

    if (condition) {
                // Statements;
                }
                else if (condition){
                // Statements;
                }
                else{
                // Statements
                }

</div>

</div>

### Switch Case Statement

It allows a variable to be tested for equality against a list of values (cases).

<div class="code-toolbar">

    switch (expression) 
                {
                case constant-expression: 
                statement1;
                statement2;
                break;
                case constant-expression: 
                statement;
                break;
                ...
                default: 
                statement;
                }

</div>

</div>

</div>

<app-adsense adtype="ad" _nghost-serverapp-c29=""></app-adsense></div>

<div>

<div>

## Iterative Statements

Iterative statements facilitate programmers to execute any block of code lines repeatedly and can be controlled as per conditions added by the programmer.

### while Loop

It allows execution of statement inside the block of the loop until the condition of loop succeeds.

<div class="code-toolbar">

    while (/* condition */)
                {
                /* code */
                }

</div>

</div>

### do-while loop

It is an exit controlled loop. It is very similar to the while loop with one difference, i.e., the body of the do-while loop is executed at least once even if the expression is false

<div class="code-toolbar">

    do
                {
                /* code */
                } while (/* condition */);

</div>

</div>

### for loop

It is used to iterate the statements or a part of the program several times. It is frequently used to traverse the data structures like the array and linked list.

<div class="code-toolbar">

    for (int i = 0; i < count; i++)
                {
                /* code */
                }

</div>

</div>

### Break Statement

break keyword inside the loop is used to terminate the loop

<div class="code-toolbar">

    break;

</div>

</div>

### Continue Statement

continue keyword skips the rest of the current iteration of the loop and returns to the starting point of the loop

<div class="code-toolbar">

    continue;

</div>

</div>

## Functions & Recursion

Functions are used to divide an extensive program into smaller pieces. It can be called multiple times to provide reusability and modularity to the C program.

### Function Definition

<div class="code-toolbar">

    return_type function_name(data_type parameter...){ 
                //code to be executed 
                }

</div>

</div>

### Recursion

Recursion is when a function calls a copy of itself to work on a minor problem. And the function that calls itself is known as the Recursive function.

<div class="code-toolbar">

    void recurse()
                {
                ... .. ...
                recurse();
                ... .. ...
                }

</div>

</div>

## Pointers

Pointer is a variable that contains the address of another variable,

### Declaration

<div class="code-toolbar">

    datatype *var_name;

</div>

</div>

## Arrays

An array is a collection of data items of the same type.

### Declaration

<div class="code-toolbar">

    data_type array_name[array_size];

</div>

</div>

### Accessing element

<div class="code-toolbar">

    int variable_name = array[index];

</div>

</div>

</div>

<app-adsense adtype="ad" _nghost-serverapp-c29=""></app-adsense></div>

<div>

<div>

## Strings

A string is a 1-D character array terminated by a null character ('\0')

### Declaration

<div class="code-toolbar">

    char str_name[size];

</div>

</div>

### gets() function

It allows you to enter multi-word string

<div class="code-toolbar">

    gets("string");

</div>

</div>

### puts() function

It is used to show string output

<div class="code-toolbar">

    puts("string");

</div>

</div>

### String Functions strlen()

It is used to calculate the length of the string

<div class="code-toolbar">

    strlen(string_name);

</div>

</div>

### strcpy() function

It is used to copy the content of second-string into the first string passed to it

<div class="code-toolbar">

    strcpy(destination, source);

</div>

</div>

### strcat() function

It is used to concatenate two strings

<div class="code-toolbar">

    strcat(first_string, second_string);

</div>

</div>

### strcmp() function

It is used to compare two strings

<div class="code-toolbar">

    strcmp(first_string, second_string);

</div>

</div>

## Structures

The structure is a collection of variables of different types under a single name. Defining structure means creating a new data type.

### Structure syntax

<div class="code-toolbar">

    struct structureName 
                {
                dataType member1;
                dataType member2;
                ...
                };

</div>

</div>

### typedef keyword

typedef function allows users to provide alternative names for the primitive and user-defined data types.

<div class="code-toolbar">

    typedef struct structureName 
                {
                dataType member1;
                dataType member2;
                ...
                }new_name;

</div>

</div>

</div>

<app-adsense adtype="ad" _nghost-serverapp-c29=""></app-adsense></div>

<div>

<div>

## File Handling

A set of methods for handling File IO (read/write/append) in C language

### FILE pointer

<div class="code-toolbar">

    FILE *filePointer;

</div>

</div>

### Opening a file

It is used to open file in C.

<div class="code-toolbar">

    filePointer = fopen(fileName.txt, w)

</div>

</div>

### fscanf() function

It is used to read the content of file.

<div class="code-toolbar">

    fscanf(FILE *stream, const char *format, ...)

</div>

</div>

### fprintf() function

It is used to write content into the file.

<div class="code-toolbar">

    fprintf(FILE *fptr, const char *str, ...);

</div>

</div>

### fgetc() function

It reads a character from a file opened in read mode. It returns EOF on reaching the end of file.

<div class="code-toolbar">

    fgetc(FILE *pointer);

</div>

</div>

### fputc() function

It writes a character to a file opened in write mode

<div class="code-toolbar">

    fputc(char, FILE *pointer);

</div>

</div>

### Closing a file

It closes the file.

<div class="code-toolbar">

    fclose(filePointer);

</div>

</div>

## Dynamic Memory Allocation

A set of functions for dynamic memory allocation from the heap. These methods are used to use the dynamic memory which makes our C programs more efficient

### malloc() function

Stands for 'Memory allocation' and reserves a block of memory with the given amount of bytes.

<div class="code-toolbar">

    ptr = (castType*) malloc(size);

</div>

</div>

### calloc() function

Stands for 'Contiguous allocation' and reserves n blocks of memory with the given amount of bytes.

<div class="code-toolbar">

    ptr = (castType*)calloc(n, size);

</div>

</div>

### free function

It is used to free the allocated memory.

<div class="code-toolbar">

    free(ptr);

</div>

</div>

### realloc() function

If the allocated memory is insufficient, then we can change the size of previously allocated memory using this function for efficiency purposes

<div class="code-toolbar">

    ptr = realloc(ptr, x);

</div>