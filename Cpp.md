<img src="https://github.com/abhayanigam/abhayanigam/blob/main/Assets/cpp.png" align="right" width="200" align="right" />

# C++ Cheatsheet

## Basics

Basic syntax and functions from the C++ programming language.

### Boilerplate

<div class="code-toolbar">

    #include <iostream>
    using namespace std;

    int main() {
    cout << "Welcome To Github";
    return 0;
    }

</div>

### cout <<

It prints output on the screen

<div class="code-toolbar">

    cout << "This is C++ Programming";

</div>

### cin >>

It takes input from the user

<div class="code-toolbar">

    cin >> variable_name;

</div>

## Data types

The data type is the type of data

### Character type

Typically a single octet(one byte). It is an integer type

<div class="code-toolbar">

    char variable_name;

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

### Boolean type

<div class="code-toolbar">

    bool

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

## Comments

A comment is a code that is not executed by the compiler, and the programmer uses it to keep track of the code.

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

## Strings

It is a collection of characters surrounded by double quotes

### Declaring String

<div class="code-toolbar">

    // Include the string library
    #include <string>

    // String variable
    string variable1 = "Hello World";

</div>

### append function

It is used to concatenate two strings

<div class="code-toolbar">

    string firstName = "Ramu";
    string lastName = "Bhai";
    string fullName = firstName.app(lastName);
    cout << fullName;

</div>

### length function

It returns the length of the string

<div class="code-toolbar">

    string variable1 = "Github";
    cout << "The length of the string is: " << variable1.length();

</div>

### Accessing and changing string characters

<div class="code-toolbar">

    string variable1 = "Hello World";
    variable1[1] = 'i';
    cout << variable1;

</div>

### Pre defined Macros Program
There are some pre defined macors and there type are :

<ol><li>__Date__ : Thee current date as a chracter in : "MM : DD : YY" format.</li>
	<li>__TIME__ : The current time as a character in "HH : MM : SS" format</li>
	<li>__FILE__ : This contains the current file name.</li>
	<li>__LINE__ : This contains current line number.</li>
</ol>

<div class="code-toolbar">

    Note :
        We can also write whole c program in C++ file.

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

    #include <iostrream>
    #define PI 3.1415

    int main()
    {
        float radius, area;
        cout << "Enter the radius: ";
        cin >> radius;

        // Notice, the use of PI
        area = PI*radius*radius;

        cout << "Area=%.2f" << area << endl;
        return 0;
    }
</div>

## Maths

C++ provides some built-in math functions that help the programmer to perform mathematical operations efficiently.

### max function

It returns the larger value among the two

<div class="code-toolbar">

    cout << max(25, 140);

</div>

### min function

It returns the smaller value among the two

<div class="code-toolbar">

    cout << min(55, 50);

</div>

### sqrt function

It returns the square root of a supplied number

<div class="code-toolbar">

    #include <cmath>
    cout << sqrt(144);

</div>

### ceil function

It returns the value of x rounded up to its nearest integer

<div class="code-toolbar">

    ceil(x)

</div>

### floor function

It returns the value of x rounded down to its nearest integer

<div class="code-toolbar">

    floor(x)

</div>

### pow function

It returns the value of x to the power of y

<div class="code-toolbar">

    pow(x, y)

</div>

## Decision Making Instructions

Conditional statements are used to perform operations based on some condition.

### If Statement

<div class="code-toolbar">

    if (condition) {
        // This block of code will geexecuted, if the condition is True
    }

</div>

### If-else Statement

<div class="code-toolbar">

    if (condition) {
        // If condition is True then this block will get executed
    } else {
        // If condition is False then this block will get executed
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

### Ternary Operator

It is shorthand of an if-else statement.

<div class="code-toolbar">

    variable = (condition) ? expressionTrue : expressionFalse;

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

## Iterative Statements

Iterative statements facilitate programmers to execute any block of code lines repeatedly and can be controlled as per conditions added by the programmer.

### while Loop

It iterates the block of code as long as a specified condition is True

<div class="code-toolbar">

    while (/* condition */)
    {
        /* code block to be executed */
    }

</div>

### do-while loop

It is an exit controlled loop. It is very similar to the while loop with one difference, i.e., the body of the do-while loop is executed at least once even if the condition is False

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

## References

Reference is an alias for an already existing variable. Once it is initialized to a variable, it cannot be changed to refer to another variable. So, it's a const pointer.

### Creating References

<div class="code-toolbar">

    string var1 = "Value1"; // var1 variable
    string &var2 = var1; // reference to var1

</div>

## Pointers

Pointer is a variable that holds the memory address of another variable

### Declaration

<div class="code-toolbar">

    datatype *var_name; 
    var_name = &variable2;

</div>

## Functions & Recursion

Functions are used to divide an extensive program into smaller pieces. It can be called multiple times to provide reusability and modularity to the C program.

### Function Definition

<div class="code-toolbar">

    return_type function_name(data_type parameter...){ 
        //code to be executed 
    }

</div>

### Function Call

<div class="code-toolbar">

    function_name(arguments);

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

## Object-Oriented Programming

It is a programming approach that primarily focuses on using objects and classes. The objects can be any real-world entities.

### class

<div class="code-toolbar">

    class Class_name {
        public: // Access specifier
                // fields
                // functions
                // blocks
    };

</div>

### object

<div class="code-toolbar">

    Class_name ObjectName;

</div>

### Constructors

It is a special method that is called automatically as soon as the object is created.

<div class="code-toolbar">

    class className { // The class
        public: // Access specifier
            className() { // Constructor
            cout << "Github";
        }
    };

    int main() {
        className obj_name; 
        return 0;
    }

</div>

### Encapsulation

Data encapsulation is a mechanism of bundling the data, and the functions that use them and data abstraction is a mechanism of exposing only the interfaces and hiding the implementation details from the user.

<div class="code-toolbar">

    #include<iostream> 
    using namespace std; 

    class ExampleEncap{ 
        private: 
    /* Since we have marked these damembers private, 
    * any entity outside this clacannot access these 
    * data members directly, they hato use getter and 
    * setter functions. 
    */ 

        int num; 
        char ch; 
        public: 

    /* Getter functions to get the valof data members. 
    * Since these functions are publithey can be accessed 
    * outside the class, thus provithe access to data members 
    * through them      
    */ 

            int getNum() const { 
            return num; 
            } 

            char getCh() const { 
            return ch; 
            } 

    /* Setter functions, they are callfor assigning the values 
    * to the private data members. 
    */ 
            void setNum(int num) { 
            this->num = num; 
            } 

            void setCh(char ch) { 
            this->ch = ch; 
            } 
    }; 
    int main(){ 
        ExampleEncap obj; 

        obj.setNum(100); 
        obj.setCh('A'); 

        cout<<obj.getNum()<<endl; 
        cout<<obj.getCh()<<endl; 

        return 0; 
    }

</div>

## File Handling

File handling refers to reading or writing data from files. C provides some functions that allow us to manipulate data in the files.

### Creating and writing to a text file

<div class="code-toolbar">

    #include <iostream>
    #include <fstream>
    using namespace std;

    int main() {
        // Create and open a text file
        ofstream MyFile("filename.txt");

        // Write to the file
        MyFile << "File Handling in C++";

        // Close the file
        MyFile.close();
    }

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

### Reading the file

It allows us to read the file line by line

<div class="code-toolbar">

    getline()

</div>

### Opening a File

It opens a file in the C++ program

<div class="code-toolbar">

    void open(const char* file_name,ios::openmode mode);

</div>

### OPEN MODES

<div class="code-toolbar">

</div>

### in

Opens the file to read(default for ifstream)

<div class="code-toolbar">

    fs.open ("test.txt", std::fstream::in)

</div>

### out

Opens the file to write(default for ofstream)

<div class="code-toolbar">

    fs.open ("test.txt", std::fstream::out)

</div>

### binary

Opens the file in binary mode

<div class="code-toolbar">

    fs.open ("test.txt", std::fstream::binary)

</div>

### app

Opens the file and appends all the outputs at the end

<div class="code-toolbar">

    fs.open ("test.txt", std::fstream::app)

</div>

### ate

Opens the file and moves the control to the end of the file

<div class="code-toolbar">

    fs.open ("test.txt", std::fstream::ate)

</div>

### trunc

Removes the data in the existing file

<div class="code-toolbar">

    fs.open ("test.txt", std::fstream::trunc)

</div>

### nocreate

Opens the file only if it already exists

<div class="code-toolbar">

    fs.open ("test.txt", std::fstream::nocreate)

</div>

### noreplace

Opens the file only if it does not already exist

<div class="code-toolbar">

    fs.open ("test.txt", std::fstream::noreplace)

</div>

### Closing a file

It closes the file

<div class="code-toolbar">

    myfile.close()

</div>

## Exception Handling

An exception is an unusual condition that results in an interruption in the flow of the program.

### try and catch block

A basic try-catch block in python. When the try block throws an error, the control goes to the except block

<div class="code-toolbar">

    try {
        // code to try
        throw exception; // If a problem arises, then throw an exception
        }catch () {
        // Block of code to handle errors
    }

</div>

## Dynamic Memory Allocation

<b>How is memory allocated/deallocated in C++?</b>
<p>C uses malloc() and calloc() function to allocate memory dynamically at run time and uses free() function to free dynamically allocated memory. C++ supports these functions and also has two operators new and delete that perform the task of allocating and freeing the memory in a better and easier way.</p>

### new operator
The new operator denotes a request for memory allocation on the Free Store. If sufficient memory is available, new operator initializes the memory and returns the address of the newly allocated and initialized memory to the pointer variable.

<div class="code-toolbar">

    //Syntax to use new operator: To allocate memory of any data type, the syntax is:

    pointer-variable = new data-type;

    // Pointer initialized with NULL
    // Then request memory for the variable
    int *p = NULL; 
    p = new int;   

                OR

    // Combine declaration of pointer 
    // and their assignment
    int *p = new int; 

</div>

### delete operator
Since it is programmer’s responsibility to deallocate dynamically allocated memory, programmers are provided delete operator by C++ language.

<div class="code-toolbar">

    // Release memory pointed by pointer-variable
    delete pointer-variable;  

</div>

### Example Program :

<div class="code-toolbar">

    // C++ program to illustrate dynamic allocation
    // and deallocation of memory using new and delete
    #include <iostream>
    using namespace std;

    int main ()
    {
        // Pointer initialization to null
        int* p = NULL;

        // Request memory for the variable
        // using new operator
        p = new(nothrow) int;
        if (!p)
            cout << "allocation of memory failed\n";
        else
        {
            // Store value at allocated address
            *p = 29;
            cout << "Value of p: " << *p << endl;
        }

        // Request block of memory
        // using new operator
        float *r = new float(75.25);

        cout << "Value of r: " << *r << endl;

        // Request block of memory of size n
        int n = 5;
        int *q = new(nothrow) int[n];

        if (!q)
            cout << "allocation of memory failed\n";
        else
        {
            for (int i = 0; i < n; i++)
                q[i] = i+1;

            cout << "Value store in block of memory: ";
            for (int i = 0; i < n; i++)
                cout << q[i] << " ";
        }

        // freed the allocated memory
        delete p;
        delete r;

        // freed the block of allocated memory
        delete[] q;

        return 0;
    }

</div>

### exit(0); function
Exit function is used to exit with program 

<div class="code-toolbar">

    #include <iostream>
    int main()
    {
        int a = 2;
        int b = 3;
        int value = a+b;

        cout << "The ans is : "<< value << endl;

        exit(0);
        retunr 0;
    }

</div>
