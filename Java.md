<img src="https://github.com/abhayanigam/abhayanigam/blob/main/Assets/Java.png" align="right" width="200" align="right" />

# Java Cheatsheet
## Basics

Basic syntax and functions from the Java programming language.

### Boilerplate

<div class="code-toolbar">

    class HelloWorld{ 
        public static void main(String args[]){ 
             System.out.println("Hello World"); 
            } 
        }

</div>

### Showing Output

It will print something to the output console.

<div class="code-toolbar">

    System.out.println([text]);

</div>

### Taking Input

It will take string input from the user

<div class="code-toolbar">

    import java.util.Scanner; //import scanner class

    // create an object of Scanner class
    Scanner input = new Scanner(System.in);

    // take input from the user
    String varName = input.nextLine();

</div>

## Primitive Type Variables

The eight primitives defined in Java are int, byte, short, long, float, double, boolean, and char those aren't considered objects and represent raw values.

### byte

byte is a primitive data type it only takes up 8 bits of memory.

<div class="code-toolbar">

    age = 18;
</div>

### long

long is another primitive data type related to integers. long takes up 64 bits of memory.

<div class="code-toolbar">

    viewsCount = 3_123_456L;

</div>

### float

We represent basic fractional numbers in Java using the float type. This is a single-precision decimal number. Which means if we get past six decimal points, this number becomes less precise and more of an estimate.

<div class="code-toolbar">

    price = 100INR;

</div>

### char

Char is a 16-bit integer representing a Unicode-encoded character.

<div class="code-toolbar">

    letter = 'A';

</div>

### boolean

The simplest primitive data type is boolean. It can contain only two values: true or false. It stores its value in a single bit.

<div class="code-toolbar">

    isEligible = true;

</div>

### int

int holds a wide range of non-fractional number values.

<div class="code-toolbar">

    var1 = 256;

</div>

### short

If we want to save memory and byte is too small, we can use short.

<div class="code-toolbar">

    short var2 = 786;

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

## Constants

Constants are like a variable, except that their value never changes during program execution.

<div class="code-toolbar">

    final float INTEREST_RATE = 0.04;

</div>

## Arithmetic Expressions

These are the collection of literals and arithmetic operators.

### Addition

It can be used to add two numbers

<div class="code-toolbar">

    int x = 10 + 3;

</div>

### Subtraction

It can be used to subtract two numbers

<div class="code-toolbar">

    int x = 10 - 3;

</div>

### Multiplication

It can be used to multiply add two numbers

<div class="code-toolbar">

    int x = 10 * 3;

</div>

### Division

It can be used to divide two numbers

<div class="code-toolbar">

    int x = 10 / 3;
    float x = (float)10 / (float)3;

</div>

### Modulo Remainder

It returns the remainder of the two numbers after division

<div class="code-toolbar">

    int x = 10 % 3;

</div>

## Augmented Operators

### Addition assignment

<div class="code-toolbar">

    var += 10 // var = var + 10

</div>

### Subtraction assignment

<div class="code-toolbar">

    var -= 10 // var = var - 10

</div>

### Multiplication assignment

<div class="code-toolbar">

    var *= 10 // var = var * 10

</div>

### Division assignment

<div class="code-toolbar">

    var /= 10 // var = var / 10

</div>

### Modulus assignment

<div class="code-toolbar">

    var %= 10 // var = var % 10

</div>

## Escape Sequences

It is a sequence of characters starting with a backslash, and it doesn't represent itself when used inside string literal.

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

### Carriage return

Inserts a carriage return in the text at this point.

<div class="code-toolbar">

    \r

</div>

### Double quote

It adds a double quotation mark

<div class="code-toolbar">

    \"

</div>

## Type Casting

Type Casting is a process of converting one data type into another

### Widening Type Casting

It means converting a lower data type into a higher

<div class="code-toolbar">

    // int x = 45;
    double var_name = x;

</div>

### Narrowing Type Casting

It means converting a higher data type into a lower

<div class="code-toolbar">

    double x = 165.48
    int var_name = (int)x;

</div>

## Decision Control Statements

Conditional statements are used to perform operations based on some condition.

### if Statement

<div class="code-toolbar">

    if (condition) {
    // block of code to be executed if the condition is true
    }

</div>

### if-else Statement

<div class="code-toolbar">

    if (condition) {
        // If condition is True then this block will get executed
    } else {
        // If condition is False then this block will get executed
    }

</div>

### if else-if Statement

<div class="code-toolbar">

    if (condition1) {
        // Codes
    }
    else if(condition2) {
        // Codes
    }
    else if (condition3) {
        // Codes
    }
    else {
        // Codes
    }

</div>

### Ternary Operator

It is shorthand of an if-else statement.

<div class="code-toolbar">

    variable = (condition) ? expressionTrue : expressionFalse;



</div>

### Switch Statements

It allows a variable to be tested for equality against a list of values (cases).

<div class="code-toolbar">

    switch(expression) {
    case a:
        // code block
        break;
    case b:
        // code block
        break;
    default:
        // code block
    }

</div>

## Iterative Statements

Iterative statements facilitate programmers to execute any block of code lines repeatedly and can be controlled as per conditions added by the coder.

### while Loop

It iterates the block of code as long as a specified condition is True

<div class="code-toolbar">

    while (condition) {
        // code block
    }

</div>

### for Loop

for loop is used to run a block of code several times

<div class="code-toolbar">

    for (initialization; termination; increment) {
        statement(s)
    }

</div>

### for-each Loop

<div class="code-toolbar">

    for(dataType item : array) {
        ...
    }

</div>

### do-while Loop

It is an exit controlled loop. It is very similar to the while loop with one difference, i.e., the body of the do-while loop is executed at least once even if the condition is False

<div class="code-toolbar">

    do {
        // body of loop
    } while(textExpression)

</div>

### Break statement

break keyword inside the loop is used to terminate the loop

<div class="code-toolbar">

    break;

</div>

### Continue statement

continue keyword skips the rest of the current iteration of the loop and returns to the starting point of the loop

<div class="code-toolbar">

    continue;

</div>

## Arrays

Arrays are used to store multiple values in a single variable

### Declaring an array

Declaration of an array

<div class="code-toolbar">

    String[] var_name;

</div>

### Defining an array

Defining an array

<div class="code-toolbar">

    String[] var_name = {''Ram", "Rohan", "Aakash"};

</div>

### Accessing an array

Accessing the elements of an array

<div class="code-toolbar">

    String[] var_name = {''Ram", "Rohan", "Aakash"};
    System.out.println(var_name[index]);

</div>

### Changing an element

Changing any element in an array

<div class="code-toolbar">

    String[] var_name = {''Ram", "Rohan", "Aakash"};
    var_name[2] = "Shubham";

</div>

### Array length

It gives the length of the array

<div class="code-toolbar">

    System.out.println(var_name.length);

</div>

### Loop through an array

It allows us to iterate through each array element

<div class="code-toolbar">

    String[] var_name = {''Ram", "Rohan", "Aakash"};
    for (int i = 0; i < var_name.length; i++) {
        System.out.println(var_name[i]);
    }

</div>

### User define array.
User define array of integer and display through for each.
<div class="code-toolbar">

        import java.util.Scanner;

        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the size :");
        int size = sc.nextInt();
        int[] arr;
        arr = new int[size];
        for (int j =0; j<arr.length;j++){
            System.out.print("Enter the element : ");
            arr[j] = sc.nextInt();
        }
        for (int k : arr){
            System.out.println(k);
        }
        sc.close();

</div>

### Multi-dimensional Arrays

Arrays can be 1-D, 2-D or multi-dimensional.

<div class="code-toolbar">

    // Creating a 2x3 array (two rows, three columns) 
    int[2][3] matrix = new int[2][3]; 
    matrix[0][0] = 10; 
    // Shortcut 
    int[2][3] matrix = { 
    { 1, 2, 3 }, 
    { 4, 5, 6 } 
    };

</div>

## Methods

Methods are used to divide an extensive program into smaller pieces. It can be called multiple times to provide reusability to the program.

### Declaration

Declaration of a method

<div class="code-toolbar">

    returnType methodName(parameters) {
        //statements
    }

</div>

### Calling a method

Calling a method

<div class="code-toolbar">

    methodName(arguments);

</div>

### Method Overloading

Method overloading means having multiple methods with the same name, but different parameters.

<div class="code-toolbar">

    class Calculate{
        void sum (int x, int y){
            System.out.println("Sum is: "+(a+b)) ;
        }
        void sum (float x, float y){
                System.out.println("Sum is: "+(a+b));
        }
        Public static void main (String[] args){
            Calculate calc = new Calculate();
            calc.sum (5,4); //sum(int x, int y) is method is called.
            calc.sum (1.2f, 5.6f); //sum(float x, float y) is called.
        }
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

## Strings

It is a collection of characters surrounded by double quotes.

### Creating String Variable

<div class="code-toolbar">

    String var_name = "Hello World";

</div>

### String Length

Returns the length of the string

<div class="code-toolbar">

    String var_name = "Ram";
    System.out.println("The length of the string is: " + var_name.length());

</div>

### String Methods toUpperCase()

Convert the string into uppercase

<div class="code-toolbar">

    String var_name = "Ram";
    System.out.println(var_name.toUpperCase());

</div>

### toLowerCase()

Convert the string into lowercase

<div class="code-toolbar">

    String var_name = ""Ram"";
    System.out.println(var_name.toLowerCase());

</div>

### indexOf()

Returns the index of specified character from the string

<div class="code-toolbar">

    String var_name = "Ram";
    System.out.println(var_name.indexOf("a"));

</div>

### concat()

Used to concatenate two strings

<div class="code-toolbar">

    String var1 = "Ram";
    String var2 = "Bhai";
    System.out.println(var1.concat(var2));

</div>

## Math Class

Math class allows you to perform mathematical operations.

### Methods max() method

It is used to find the greater number among the two

<div class="code-toolbar">

    Math.max(25, 45);

</div>

### min() method

It is used to find the smaller number among the two

<div class="code-toolbar">

    Math.min(8, 7);

</div>

### sqrt() method

It returns the square root of the supplied value

<div class="code-toolbar">

    Math.sqrt(144);

</div>

### random() method

It is used to generate random numbers

<div class="code-toolbar">

    Math.random(); //It will produce random number b/w 0.0 and 1.0

</div>

<div class="code-toolbar">

    int random_num = (int)(Math.random() * 101); //Random num b/w 0 and 100

</div>

## Object-Oriented Programming

It is a programming approach that primarily focuses on using objects and classes. The objects can be any real-world entities.

### object

An object is an instance of a Class.

<div class="code-toolbar">

    className object = new className();

</div>

### class

A class can be defined as a template/blueprint that describes the behavior/state that the object of its type support.

<div class="code-toolbar">

    class ClassName {
        // Fields
        // Methods
        // Constructors
        // Blocks
    }

</div>

### Encapsulation

Encapsulation is a mechanism of wrapping the data and code acting on the data together as a single unit. In encapsulation, the variables of a class will be hidden from other classes and can be accessed only through the methods of their current class.

<div class="code-toolbar">

    public class Person { 
        private String name; // using private access modifier 

        // Getter 
        public String getName() { 
            return name; 
        } 

        // Setter 
        public void setName(String newName) { 
            this.name = newName; 
        } 
    }

</div>

### Inheritance

Inheritance can be defined as the process where one class acquires the properties of another. With the use of inheritance the information is made manageable in a hierarchical order.

<div class="code-toolbar">

    class Subclass-name extends Superclass-name { 
        //methods and fields 
    }



</div>

### Polymorphism

Polymorphism is the ability of an object to take on many forms. The most common use of polymorphism in OOP occurs when a parent class reference is used to refer to a child class object.

<div class="code-toolbar">

    // A class with multiple methods with the same name 
    public class Adder { 
        // method 1 
        public void add(int a, int b) { 
            System.out.println(a + b); 
        } 

        // method 2 
        public void add(int a, int b, int c) { 
            System.out.println(a + b + c); 
        } 

        // method 3 
        public void add(String a, String b) { 
            System.out.println(a + " + " + b); 
        } 
    } 

    // My main class 
    class MyMainClass { 
        public static void main(String[] args) { 
            Adder adder = new Adder(); // create a Adder object 
            adder.add(5, 4); // invoke method 1 
            adder.add(5, 4, 3); // invoke method 2 
            adder.add("5", "4"); // invoke method 3 
        } 
    }

</div>

## File Operations

File handling refers to reading or writing data from files. Java provides some functions that allow us to manipulate data in the files.

### canRead method

Checks whether the file is readable or not

<div class="code-toolbar">

    file.canRead()

</div>

### createNewFile method

It creates an empty file

<div class="code-toolbar">

    file.createNewFile()

</div>

### canWrite method

Checks whether the file is writable or not

<div class="code-toolbar">

    file.canWrite()

</div>

### exists method

Checks whether the file exists

<div class="code-toolbar">

    file.exists()

</div>

### delete method

It deletes a file

<div class="code-toolbar">

    file.delete()

</div>

### getName method

It returns the name of the file

<div class="code-toolbar">

    file.getName()

</div>

### getAbsolutePath method

It returns the absolute pathname of the file

<div class="code-toolbar">

    file.getAbsolutePath()

</div>

### length Method

It returns the size of the file in bytes

<div class="code-toolbar">

    file.length()

</div>

### list Method

It returns an array of the files in the directory

<div class="code-toolbar">

    file.list()

</div>

### mkdir method

It is used to create a new directory

<div class="code-toolbar">

    file.mkdir()

</div>

### close method

It is used to close the file

<div class="code-toolbar">

    file.close()

</div>

### To write something in the file

<div class="code-toolbar">

    import java.io.FileWriter; // Import the FileWriter class
    import java.io.IOException; // Import the IOException class to handle errors

    public class WriteToFile {
        public static void main(String[] args) {
        try {
            FileWriter myWriter = new FileWriter("filename.txt");
            myWriter.write("Laal Phool Neela Phool, Ram Bhaiya Beautiful");
            myWriter.close();
            System.out.println("Successfully wrote to the file.");
            } catch (IOException e) {
                System.out.println("An error occurred.");
                e.printStackTrace();
            }
        }
    }

</div>

## Exception Handling

An exception is an unusual condition that results in an interruption in the flow of the program.

### try-catch block

try statement allow you to define a block of code to be tested for errors. catch block is used to handle the exception.

<div class="code-toolbar">

    try {
        // Statements
    }
    catch(Exception e) {
        // Statements
    }

</div>

### finally block

finally code is executed whether an exception is handled or not.

<div class="code-toolbar">

    try {
        //Statements
    }
    catch (ExceptionType1 e1) { 
        // catch block
    }
        finally {
        // finally block always executes
    }

</div>
