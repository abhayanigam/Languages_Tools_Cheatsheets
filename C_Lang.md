<img src="https://github.com/abhayanigam/Learn_C/blob/main/c.png" align="right" width="200" align="right" />

# C Language CheatSheet

## Basics

Basic syntax and functions from the C programming language.

### Boilerplate Code

<div class="code-toolbar">

    #include<stdio.h>
    int main(){
        return(0);
    }

</div>

### printf function

It is used to show output on the screen

<div class="code-toolbar">

    printf("Hello World!");

</div>

### Basic types

Here's a table containing commonly used types in C programming for quick access.

<table border="0" cellpadding="1" cellspacing="1"><thead><tr><th scope="col">Type</th>
			<th scope="col">Size (bytes)</th>
			<th scope="col">Format Specifier</th>
		</tr></thead><tbody><tr><td><code>int</code></td>
			<td>at least 2, usually 4</td>
			<td><code>%d</code>, <code>%i</code></td>
		</tr><tr><td><code>char</code></td>
			<td>1</td>
			<td><code>%c</code></td>
		</tr><tr><td><code>float</code></td>
			<td>4</td>
			<td><code>%f</code></td>
		</tr><tr><td><code>double</code></td>
			<td>8</td>
			<td><code>%lf</code></td>
		</tr><tr><td><code>short int</code></td>
			<td>2 usually</td>
			<td><code>%hd</code></td>
		</tr><tr><td><code>unsigned int</code></td>
			<td>at least 2, usually 4</td>
			<td><code>%u</code></td>
		</tr><tr><td><code>long int</code></td>
			<td>at least 4, usually 8</td>
			<td><code>%ld</code>, <code>%li</code></td>
		</tr><tr><td><code>long long int</code></td>
			<td>at least 8</td>
			<td><code>%lld</code>, <code>%lli</code></td>
		</tr><tr><td><code>unsigned long int</code></td>
			<td>at least 4</td>
			<td><code>%lu</code></td>
		</tr><tr><td><code>unsigned long long int</code></td>
			<td>at least 8</td>
			<td><code>%llu</code></td>
		</tr><tr><td><code>signed char</code></td>
			<td>1</td>
			<td><code>%c</code></td>
		</tr><tr><td><code>unsigned char</code></td>
			<td>1</td>
			<td><code>%c</code></td>
		</tr><tr><td><code>long double</code></td>
			<td>at least 10, usually 12 or 16</td>
			<td><code>%Lf</code></td>
		</tr></tbody></table>
	
### scanf function

It is used to take input from the user

<div class="code-toolbar">

    scanf("placeholder", variables);

</div>

## Comments

A comment is the code that is not executed by the compiler, and the programmer uses it to keep track of the code.

### Single line comment

<div class="code-toolbar">

    // It's a single line comment

</div>

### Multi-line comment

<div class="code-toolbar">

    /* 
        It's a 
        multi-line
        comment                
    */

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

### Float type

A single-precision floating-point value

<div class="code-toolbar">

    float variable_name;

</div>

### Double type

A double-precision floating-point value

<div class="code-toolbar">

    double variable_name;

</div>

### Void type

Represents the absence of the type

<div class="code-toolbar">

    void

</div>

## Escape Sequences

It is a sequence of characters starting with a backslash, and it doesn't represent itself when used inside string literal.

### Alarm or Beep

It produces a beep sound

<div class="code-toolbar">

    \a

</div>

### Backspace

It adds a backspace

<div class="code-toolbar">

    \b

</div>

### Form feed

<div class="code-toolbar">

    \f

</div>

### Newline

Newline Character

<div class="code-toolbar">

    \n

</div>

### Carriage return

<div class="code-toolbar">

    \r

</div>

### Tab

It gives a tab space

<div class="code-toolbar">

    \t

</div>

### Backslash

It adds a backslash

<div class="code-toolbar">

    \\

</div>

### Single quote

It adds a single quotation mark

<div class="code-toolbar">

    \'

</div>

### Question mark

It adds a question mark

<div class="code-toolbar">

    \?

</div>

### Octal No.

It represents the value of an octal number

<div class="code-toolbar">

    \nnn

</div>

### Hexadecimal No.

It represents the value of a hexadecimal number

<div class="code-toolbar">

    \xhh

</div>

### Null

The null character is usually used to terminate a string

<div class="code-toolbar">

    \0

</div>

## Conditional Instructions

Conditional statements are used to perform operations based on some condition.

### If Statement

<div class="code-toolbar">

    if (/* condition */){
        /* code */
    }

</div>

### If-else Statement

<div class="code-toolbar">

    if (/* condition */){
        /* code */
    }
    else{
        /* Code */
    }


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

### Switch Case Statement

It allows a variable to be tested for equality against a list of values (cases).

<div class="code-toolbar">

    switch (expression) {
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

## Iterative Statements

Iterative statements facilitate programmers to execute any block of code lines repeatedly and can be controlled as per conditions added by the programmer.

### while Loop

It allows execution of statement inside the block of the loop until the condition of loop succeeds.

<div class="code-toolbar">

    while (/* condition */){
        /* code */
    }

</div>

### do-while loop

It is an exit controlled loop. It is very similar to the while loop with one difference, i.e., the body of the do-while loop is executed at least once even if the expression is false

<div class="code-toolbar">

    do{
        /* code */
    } while (/* condition */);

</div>

### for loop

It is used to iterate the statements or a part of the program several times. It is frequently used to traverse the data structures like the array and linked list.

<div class="code-toolbar">

    for (int i = 0; i < count; i++){
        /* code */
    }

</div>

### Break Statement

break keyword inside the loop is used to terminate the loop

<div class="code-toolbar">

    break;

</div>

### Continue Statement

continue keyword skips the rest of the current iteration of the loop and returns to the starting point of the loop

<div class="code-toolbar">

    continue;

</div>

## Functions & Recursion

Functions are used to divide an extensive program into smaller pieces. It can be called multiple times to provide reusability and modularity to the C program.

### Function Definition

<div class="code-toolbar">

    return_type function_name(data_type parameter...){ 
        //code to be executed 
    }

</div>

### Recursion

Recursion is when a function calls a copy of itself to work on a minor problem. And the function that calls itself is known as the Recursive function.

<div class="code-toolbar">

    void recurse(){
        ... .. ...
        recurse();
        ... .. ...
    }

</div>

## Pointers

Pointer is a variable that contains the address of another variable,

### Declaration

<div class="code-toolbar">

    datatype *var_name;

</div>

## Arrays

An array is a collection of data items of the same type.

### Declaration

<div class="code-toolbar">

    data_type array_name[array_size];

</div>

### Accessing element

<div class="code-toolbar">

    int variable_name = array[index];

</div>

## Strings

A string is a 1-D character array terminated by a null character ('\0')

### Declaration

<div class="code-toolbar">

    char str_name[size];

</div>

### gets() function

It allows you to enter multi-word string

<div class="code-toolbar">

    gets("string");

</div>

### puts() function

It is used to show string output

<div class="code-toolbar">

    puts("string");

</div>

### String Functions strlen()

It is used to calculate the length of the string
<p><strong>&lt;string.h&gt; is used to perform string functions</strong></p>

<div class="code-toolbar">

    strlen(string_name);

</div>

### strcpy() function

It is used to copy the content of second-string into the first string passed to it

<div class="code-toolbar">

    strcpy(destination, source);

</div>

### strcat() function

It is used to concatenate two strings

<div class="code-toolbar">

    strcat(first_string, second_string);

</div>

### strcmp() function

It is used to compare two strings

<div class="code-toolbar">

    strcmp(first_string, second_string);

</div>

### Pre defined Macros Program
There are some pre defined macors and there type are :

<ol><li>__Date__ : Thee current date as a chracter in : "MM : DD : YY" format.</li>
	<li>__TIME__ : The current time as a character in "HH : MM : SS" format</li>
	<li>__FILE__ : This contains the current file name.</li>
	<li>__LINE__ : This contains current line number.</li>
</ol>

<div class="code-toolbar">

    #include <stdio.h>
    int main()
    {
        printf("Current time: %s",__TIME__);
        printf("Current Date: %s",__DATE__);
        printf("Current file name: %s",__FILE__);
        printf("Current line number: %s",__LINE__);

        return 0;
    }

</div>

### Macros using #define
A macro is a fragment of code that is given a name. You can define a macro in C using the #define preprocessor directive.

<p><strong>Here's an example.

#define PI 3.1415 // Value of PI</strong></p>

<div class="code-toolbar">

    #include <stdio.h>
    #define PI 3.1415

    int main()
    {
        float radius, area;
        printf("Enter the radius: ");
        scanf("%f", &radius);

        // Notice, the use of PI
        area = PI*radius*radius;

        printf("Area=%.2f",area);
        return 0;
    }
</div>

## Structures

The structure is a collection of variables of different types under a single name. Defining structure means creating a new data type.

### Structure syntax

<div class="code-toolbar">

    struct structureName {
        dataType member1;
        dataType member2;
        ...
    };

</div>

### typedef keyword

typedef function allows users to provide alternative names for the primitive and user-defined data types.

<div class="code-toolbar">

    typedef struct structureName {
        dataType member1;
        dataType member2;
        ...
    }new_name;

</div>

## File Handling

A set of methods for handling File IO (read/write/append) in C language

### FILE pointer

<div class="code-toolbar">

    FILE *filePointer;

</div>

### Opening Modes

<table summary="Different opening modes for standard input/output in C programming." border="0"><caption>Opening Modes in Standard I/O</caption>
	<thead><tr><th>Mode</th>
			<th>Meaning of Mode</th>
			<th>During Inexistence of file</th>
		</tr></thead><tbody><tr><td><code>r</code></td>
			<td>Open for reading.</td>
			<td>If the file does not exist, <code>fopen()</code> returns NULL.</td>
		</tr><tr><td><code>rb</code></td>
			<td>Open for reading in binary mode.</td>
			<td>If the file does not exist, <code>fopen()</code> returns NULL.</td>
		</tr><tr><td><code>w</code></td>
			<td>Open for writing.</td>
			<td>If the file exists, its contents are overwritten.<br>
				If the file does not exist, it will be created.</td>
		</tr><tr><td><code>wb</code></td>
			<td>Open for writing in binary mode.</td>
			<td>If the file exists, its contents are overwritten.<br>
				If the file does not exist, it will be created.</td>
		</tr><tr><td><code>a</code></td>
			<td>Open for append.<br>
				Data is added to the end of the file.</td>
			<td>If the file does not exist, it will be created.</td>
		</tr><tr><td><code>ab</code></td>
			<td>Open for append in binary mode.<br>
				Data is added to the end of the file.</td>
			<td>If the file does not exist, it will be created.</td>
		</tr><tr><td><code>r+</code></td>
			<td>Open for both reading and writing.</td>
			<td>If the file does not exist, <code>fopen()</code> returns NULL.</td>
		</tr><tr><td><code>rb+</code></td>
			<td>Open for both reading and writing in binary mode.</td>
			<td>If the file does not exist, <code>fopen()</code> returns NULL.</td>
		</tr><tr><td><code>w+</code></td>
			<td>Open for both reading and writing.</td>
			<td>If the file exists, its contents are overwritten.<br>
				If the file does not exist, it will be created.</td>
		</tr><tr><td><code>wb+</code></td>
			<td>Open for both reading and writing in binary mode.</td>
			<td>If the file exists, its contents are overwritten.<br>
				If the file does not exist, it will be created.</td>
		</tr><tr><td><code>a+</code></td>
			<td>Open for both reading and appending.</td>
			<td>If the file does not exist, it will be created.</td>
		</tr><tr><td><code>ab+</code></td>
			<td>Open for both reading and appending in binary mode.</td>
			<td>If the file does not exist, it will be created.</td>
		</tr></tbody></table>

### Opening a file

It is used to open file in C.

<div class="code-toolbar">

    filePointer = fopen(fileName.txt, w)

</div>

### fscanf() function

It is used to read the content of file.

<div class="code-toolbar">

    fscanf(FILE *stream, const char *format, ...)

</div>

### fprintf() function

It is used to write content into the file.

<div class="code-toolbar">

    fprintf(FILE *fptr, const char *str, ...);

</div>

### fgetc() function

It reads a character from a file opened in read mode. It returns EOF on reaching the end of file.

<div class="code-toolbar">

    fgetc(FILE *pointer);

</div>

### fputc() function

It writes a character to a file opened in write mode

<div class="code-toolbar">

    fputc(char, FILE *pointer);

</div>

### Closing a file

It closes the file.

<div class="code-toolbar">

    fclose(filePointer);

</div>

## Dynamic Memory Allocation

A set of functions for dynamic memory allocation from the heap. These methods are used to use the dynamic memory which makes our C programs more efficient
<p><strong>&lt;stdlib.h&gt; header file is used in memory allocation functions</strong></p>

### malloc() function

Stands for 'Memory allocation' and reserves a block of memory with the given amount of bytes.

<div class="code-toolbar">

    // ptr = (int*)malloc(number of blocks * size of each block in byte)
    ptr = (castType*) malloc(size);
    
    Example:
        ptr = (int *)malloc(n*sizeof(int));

</div>

### calloc() function

Stands for 'Contiguous allocation' and reserves n blocks of memory with the given amount of bytes.

<div class="code-toolbar">

    // ptr = (int*)malloc(number of blocks, size of each block in byte)
    ptr = (castType*)calloc(n, size);

</div>

### free function

It is used to free the allocated memory.

<div class="code-toolbar">

    free(ptr);

</div>

### realloc() function

If the allocated memory is insufficient, then we can change the size of previously allocated memory using this function for efficiency purposes

<div class="code-toolbar">

    ptr = realloc(ptr, x);

</div>

### exit(0); function
Exit function is used to exit with program 

<div class="code-toolbar">

    #include <stdio.h>
    int main()
    {
        int a = 2;
        int b = 3;
        int value = a+b;

        printf("The ans is : %d\n",value);

        exit(0);
        retunr 0;
    }

</div>
