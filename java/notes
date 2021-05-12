# Introduction:

[https://www.notion.so/Masai-Java-Notes-6e0696100d0b4a78b80cf0771459966b](https://www.notion.so/Masai-Java-Notes-6e0696100d0b4a78b80cf0771459966b)

JAVA was developed by Sun Microsystems Inc in 1991, later acquired by
 Oracle Corporation. It was developed by James Gosling and Patrick 
Naughton. It is a simple programming language.  Writing, compiling and 
debugging a program is easy in java.  It helps to create modular 
programs and reusable code.

## Features of Java:

Apart from being a system independent language, there are other 
reasons too for the immense popularity of this language. Let us have a 
look at some of its features

1. Simple
Java is a simple programming language. Rather than saying this is the
feature of Java, we can say this is the design aim of Java. When Java is developed they wanted it to be simple because it has to work on
electronic devices where less memory is available. Now the question is
how Java is made simple ? All the difficult concepts of C, C++ have been omitted in java. For example the concept of pointers which is very
difficult for both learners and programmers has been completely
eliminated in java.
2. Object-Oriented
Java is an object oriented programming language. This means java programs use object and classes.
3. Robust
Robust means strong. Java programs are strong and they dont crash
easily. There are two reasons for this. Firstly, Java has got excellent
inbuilt exception handling. Another reason lies in its memory management features. Most of the C, C++ programs crash in the middle because of
not allocating sufficient memory or forgetting the memory to be freed in a program. Such problems will not occur in Java because the user need
not allocate or deallocate the memory in java. Everything will be taken
care by the JVM only. For example , JVM will allocate the necessary
memory required by a Java program.
4. Secure
Security problems like tampering, impersonation and virus threats can be eliminated or minimied by uing java on interent.
5. System independent

Java's byte code is not machine dependent. It can be run on any machine with any processor and any operating system.

1. Portability:
If a program yields the same result on every machine , then that program is called portable Java programs are portable this is because of its
System independent nature.
2. Interpreted:
Java programs are compiled to generate byte code. This byte code can be
downloaded and interpretted by the interpretter in JVM. If we take any
other language only a compiler or interpretter is used to execute a
program. But in java we use both compiler and interpretter for
execution.
3. MultiThreaded

## What is Java Virtual Machine (JVM) ?

Java Virtual machine is the heart of entire Java program execution 
process. It is responsible for taking the .class file and converting 
each byte code instruction into machine language instruction that can be
 exeuted by the microprocessor.

First of all, the .java program is converted into a .class file 
consisting of byte code instructions by the java compiler. Remember, 
this java compiler is outside the JVM. Now this .class file is given to 
the JVM. In JVM, there is a module called class loader sub system , 
which performs the following functions:

1. First of all, it loads the .class files into memory.
2. Then it verifies whether all byte code instructions are proper or
not. If it finds any instruction suspicious, the execution is rejected
immediately.
3. If the byte instructions are proper, then it allocates necessary memory to execute the program.

This memory is diveded into 5 parts:

## Method area:

Method area is the memory block which stores the class code, code of the variables and the code of methods in the java program.

## Heap:

This is the area where objects are created. Whenever JVM loads a class, a method and heap area are immediately created in it.

## Java Stacks:

Method code is stored in method area. But while running a method, it 
needs some more memory to store the data and results. This memory is 
allocated on java stack. So java stacks are memory areas where java 
methods are executed.

## Program Counter (PC) :

These are registers, which contain memory address of the instructions
 of the methods. If there are 3 methods, 3 PC registers will be used to 
track the instructions of the methods.

## Native method stack:

Java methods are executed on java stacks. Similarly, native methods 
are executed on Native method stacks. To execute the native methods, 
generally native method libraries(for example C/C++ header files) are 
required. These header files are located and connected to JVM by a 
program called Java Native Interface (JNI).

# Java Syntax:

```
    public class MyClass {
      public static void main(String[] args) {
      System.out.println("Hello World");
      }
    }
```

Every line of code that runs in Java must be inside a class. In our 
example, we named the class MyClass. A class should always start with an
 uppercase first letter.

**Note:**

Java is case-sensitive: "MyClass" and "myclass" has different 
meaning. The name of the java file must match the class name. When 
saving the file, save it using the class name and add ".java" to the end
 of the filename

## The main Method:

The `main()` method is required and you will see it in every Java program:

```
public static void main(String[] args);
```

**main()** is the point where the program starts executing.

## System.out.println():

We can use the println() method to print a line of text to the screen:

## Note:

1.The curly braces {} marks the beginning and the end of a block of code.
2.Each code statement must end with a semicolon.

## Java Comments:

Comments can be used to explain Java code, and to make it more 
readable. It can also be used to prevent execution when testing 
alternative code.

Single-line comments start with two forward slashes (//).

Any text between // and the end of the line is ignored by Java (will not be executed).

This example uses a single-line comment before a line of code:

## Example:

```
// This is a comment
System.out.println("Hello World");
```

**Output**

```
Hello World
```

## Java Multi-line Comments:

Multi-line comments start with /* and ends with */.

Any text between /* and */ will be ignored by Java.

This example uses a multi-line comment (a comment block) to explain the code:

## Example:

```
/* The code below will print the words Hello World
to the screen, and it is amazing */
System.out.println("Hello World");
```

**Output**

```
Hello World
```

For more information [refer](https://www.w3schools.com/java/java_variables.asp)

# Datatypes

## Data types are divided into two groups:

Primitive data types - includes byte, short, int, long, float, double, boolean and char
Non-primitive data types - such as String, Arrays and Classes.

## Integer Types

## byte

The byte data type can store whole numbers from -128 to 127. This can
 be used instead of int or other integer types to save memory when you 
are certain that the value will be within -128 and 127:

**Example**

```
    byte myNum = 100;
    System.out.println(myNum);
```

**Output**

```
100
```

## short

The short data type can store whole numbers from -32768 to 32767:

**Example**

```
    short myNum = 5000;
    System.out.println(myNum)
```

**Output**

```
5000
```

## int

The int data type can store whole numbers from -2147483648 to 
2147483647. In general, and in our tutorial, the int data type is the 
preferred data type when we create variables with a numeric value.

**Example**

```
    int myNum = 100000;
    System.out.println(myNum);
```

**Output**

```
100000
```

## long

The long data type can store whole numbers from -9223372036854775808 
to 9223372036854775807. This is used when int is not large enough to 
store the value. Note that you should end the value with an "L":

**Example**

```
    long myNum = 15000000000L;
    System.out.println(myNum);
```

**Output**

```
15000000000
```

## Floating Point Types

You should use a floating point type whenever you need a number with a decimal, such as 9.99 or 3.14515.

## float

The float data type can store fractional numbers from 3.4e−038 to 
3.4e+038. Note that you should end the value with an "f": Float gives a 
accuracy of upto 6 or 7 digits after decimal points.

**Example 1**

```
    float myNum = 5.75f;
    System.out.println(myNum);
```

**Output**

```
5.75
```

**Example 2**

```
    float value = 50.786868685678f;
    System.out.println(value);
```

**Output**

```
50.7868686
```

## double

The double data type can store fractional numbers from 1.7e−308 to 1.7e+308. The `double` gives an accuracy upto 15 digits after decimal points.

**Example**

```
    double myNum = 19.999191191919;
    System.out.println(myNum);
```

**Output**

```
19.999191191919
```

## boolean

A boolean data type is declared with the boolean keyword and can only take the values true or false:

**Example**

```
    boolean isJavaFun = true;
    boolean isFishTasty = false;
    System.out.println(isJavaFun);     // Outputs true
    System.out.println(isFishTasty);   // Outputs false
```

## char

The char data type is used to store a single character. The character must be surrounded by single quotes, like 'A' or 'c':

**Example**

```
    char myGrade = 'B';
    System.out.println(myGrade);
```

# Java Variables

**Syntax:**

```
    type variable = value;
```

Variables are containers for storing data values.

In Java, there are different types of variables, for example:

- String - stores text, such as "Hello". String values are surrounded by double quotes
- int - stores integers (whole numbers), without decimals, such as 123 or -123
- float - stores floating point numbers, with decimals, such as 19.99 or -19.99
- char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
- boolean - stores values with two states: true or false

**Example**

Create a variable called value of type String and assign it the value "Masai"

```
    String value = "Masai";
    System.out.println(value);
```

**Output**

```
Masai
```

To create a variable that should store a number, look at the following example:

**Example**

Create a variable called myNum of type int and assign it the value 15:

```
    int myNum = 15;
    System.out.println(myNum);
```

**Output**

```
15
```

You can also declare a variable without assigning the value, and assign the value later:

**Example**

```
    int myNum;
    myNum = 15;
    System.out.println(myNum);
```

**Output**

```
15
```

Note that if you assign a new value to an existing variable, it will overwrite the previous value:

**Example**

Change the value of myNum from 15 to 20:

```
    int myNum = 15;
    myNum = 20;  // myNum is now 20
    System.out.println(myNum);
```

**Output**

```
20
```

## Other Types

A demonstration of how to declare variables of other types:

**Example**

```
    int myNum = 5;
    float myFloatNum = 5.99f;
    char myLetter = 'D';
    boolean myBool = true;
    String myText = "Hello";
```

# Java Operators

Java divides the operators into the following groups:

- Arithmetic operators
- Assignment operators
- Comparison operators
- Logical operators
- Bitwise operators

## Arithmetic Operators

- , - , * , / , %

**Example 1**

```
int a = 4;
int b = 5;
int c = a+b;
System.out.println(c);
```

**Output**

```
9
```

**Example 2**

```
int a = 3;
int b = 4;
int c = a-b;
System.out.println(c);
```

**Output**

```
-1
```

**Example 3**

```
float x = 1.00f;
float y = 2.00f;
float z = x/y;
System.out.println(z);
```

**Output**

```
0.5
```

**Example 4:**

```
int a = 10:
int b = 9:
int c = a%b;
System.out.println(c);
```

**Output**

```
1
```

## Assignment Operators

Assignment operators are used to assign values to variables.

In the example below, we use the assignment operator (=) to assign the value 10 to a variable called x:

**Example**

```
    int x = 10;
    System.out.println(x);
```

**Output**

```
10
```

The addition assignment operator (+=) adds a value to a variable:

**Example**

```
    int x = 10;
    x += 5;
    System.out.println(x);
```

**Output**

```
15
```

## Unary Arithmetic Operators

In Java, unary arithmetic operators are used to increasing or 
decreasing the value of an operand. Increment operator adds 1 to the 
value of a variable, whereas the decrement operator decreases a value.

Increment and decrement unary operator works as follows:

**Syntax:**

```
    val++;
    val--;

```

These two operators have two forms: Postfix and Prefix. Both do 
increment or decrement in appropriate variables. These two operators can
 be placed before or after of variables. When it is placed before the 
variable, it is called prefix. And when it is placed after, it is called
 postfix.

- val = a++; //Store the value of "a" in "val" then increments.
- val = a--; //Store the value of "a" in "val" then decrements.
- val = ++a; //Increments "a" then store the new value of "a" in "val".
- val = --a; //Decrements "a" then store the new value of "a" in "val".

## Comparison Operators

== , != , > , < , >= , <=

**Example 1**

```
int a = 10;
boolean b = a>5;
System.out.println(b);
```

**Output**

```
true
```

**Example 2**

```
int x = 10;
boolean y = (x==10);
```

**Output**

```
true
```

## Logical Operators

&& , || , !

**Example 1**

```
int a = 20;
int b = 10;
boolean z = (a>b) && (b<a);
System.out.println(z);
```

**Output**

```
true
```

**Example 2**

```
int a = 20;
int b = 1;
boolean y = (a>b) || (b>a);
System.out.println(y);
```

**Output**

```
true
```

**Example 3**

```
int a = 12;
int b = 21;
boolean z = ((a>b) || (b >0)) && (a !=0);
System.out.println(z);
```

**Output**

```
true
```

**Example 4**

```
boolean isAssignmentCompleted = true;
boolean negate = !isAssignmentCompleted;
System.out.println(negate);
```

**Output**

```
false
```

# Conditional statements

1. **The if Statement**

Use the if statement to specify a block of Java code to be executed if a condition is true.

**Syntax**

```
    if (condition) {
      // block of code to be executed if the condition is true
    }
```

**Note**

`if` is in lowercase letters. Uppercase letters (If or IF) will generate an error.

In the example below, we test two values to find out if 20 is greater than 18. If the condition is true, print some text:

**Example**

```
    if (20 > 18) {
      System.out.println("20 is greater than 18");
    }
```

1. **The else Statement**

Use the else statement to specify a block of code to be executed if the condition is false.

**Syntax**

```
    if (condition) {
      // block of code to be executed if the condition is true
    } else {
      // block of code to be executed if the condition is false
    }
```

**Example 1**

```
    int time = 20;
    if (time < 18) {
      System.out.println("Good day.");
    } else {
      System.out.println("Good evening.");
    }
```

**Output**

```
Good evening
```

**Example 2**

```
int n = 5;

if(n%2==0) {
  System.out.println("n is even");
}
else {
  System.out.println("n is odd");
}

```

**Output**

```
n is odd
```

1. **The else if Statement**

Use the else if statement to specify a new condition if the first condition is false.

**Syntax**

```
    if (condition1) {
      // block of code to be executed if condition1 is true
    } else if (condition2) {
     // block of code to be executed if the condition1 is false and condition2 is true
    } else {
     // block of code to be executed if the condition1 is false and condition2 is false
    }
```

**Example 1**

```
    int time = 22;
    if (time < 10) {
      System.out.println("Good morning.");
    } else if (time < 20) {
      System.out.println("Good day.");
    } else {
      System.out.println("Good evening.");
    }
```

**Output**

```
Good evening.
```

**Example 2**

```
public class Test {
    public static void main(String[] args) {
        int a = 10;
        int b = 3;
        if (a > 5 && b > 5) {
            System.out.println(" a>5, b>5");
        } else if (a > 5 && b < 5) {
            System.out.println(" a>5, b<5");
        } else if (a < 5 && b > 5) {
            System.out.println(" a<5, b>5");
        } else if (a < 5 && b < 5) {
            System.out.println(" a<5, b<5");
        }
    }
}

```

**Output**

```
a>5, b<5
```

# Ternary operator

**Syntax:**

```
condition ? true : false
```

**Example:**

```
string result;

result = (6>5) ? "6 is greater than 5" : " 6 is not greater than 5" ;
System.out.println(result);

```

**Output**

```
6 is greater than 5
```

**Nested if Conditions**

**Syntax:**

```
if(condition1)
{
   if(condition2)
   {
      //Statements
   } else
   {
      //Statements
   }
} else
{
   // Statements
}
```

**Example**

```
public class Masai {
    public static void main(String[] args) {
        int a = 10;
        int b = 3;
        if (a > 5) {

            if (b > 5) {
                System.out.println("a>5 , b>5");
            } else {
                System.out.println("a>5 , b<5");
            }
        } else {
            if (b > 5) {
                System.out.println("a<5 , b>5");
            } else {
                System.out.println("a<5 , b<5");
            }
        }
    }
}
```

**Output**

```
a>5 , b<5
```

# Switch Statement

The switch statement evaluates an value and matches the value to various **cases**.

It then executes the code associated with each statement until it encounters a `break` statement.

**Syntax:**

```
switch (expression) {
  case value1:
    //Statements executed when the
    //result of expression matches value1
    [break;]
  case value2:
    //Statements executed when the
    //result of expression matches value2
    [break;]
  ...
  case valueN:
    //Statements executed when the
    //result of expression matches valueN
    [break;]
  [default:
    //Statements executed when none of
    //the values match the value of the expression
    [break;]]
```

```
}
```

**Example:**

```
int day = 6
switch (day) {
  case 0:
    day = "Sunday";
    break;
  case 1:
    day = "Monday";
    break;
  case 2:
    day = "Tuesday";
    break;
  case 3:
    day = "Wednesday";
    break;
  case 4:
    day = "Thursday";
```

```
  break;
  case 5:
    day = "Friday";
    break;
  case 6:
    day = "Saturday";
    break;
  default:
    day = "Invalid Input";
}

System.out.println(day);
```

**Output**

```
Saturday
```

# Loops

Loops can execute a block of code as long as a specified condition is reached.

Loops are handy because they save time, reduce errors, and they make code more readable.

1. **While Loop**

The while loop loops through a block of code as long as a specified condition is true:

**Syntax**

```
     while (condition) {
       // code block to be executed
     }
```

**Example**

```
    int i = 0;
    while (i < 5) {
       System.out.println(i);
       i++;
    }
```

**Output**

```
0
1
2
3
4
```

**Note:**

Do not forget to increase the variable used in the condition, otherwise the loop will never end!

1. **Do/While Loop**

The do/while loop is a variant of the while loop. This loop will 
execute the code block once, before checking if the condition is true, 
then it will repeat the loop as long as the condition is true.

**Syntax**

```
    do {
      // code block to be executed
      }
    while (condition);

```

The loop will always be executed at least once, even if the condition
 is false, because the code block is executed before the condition is 
tested:

**Example**

```
    int i = 10;
    do {
       System.out.println(i);
       i++;
      }
    while (i < 5);
```

**Output**

```
10
```

1. **For Loop:**

When you know exactly how many times you want to loop through a block of code, use the for loop instead of a while loop:

**Syntax**

```
    for (statement 1; statement 2; statement 3) {
      // code block to be executed
    }
```

Statement 1 is executed (one time) before the execution of the code block.

Statement 2 defines the condition for executing the code block.

Statement 3 is executed (every time) after the code block has been executed.

**Example 1**

```
    for (int i = 0; i < 5; i++) {
      System.out.println(i);
    }
```

**Output**

```
0
1
2
3
4
```

**Example2**

```
for (int i = 0; i <= 10; i = i + 2) {
  System.out.println(i);
}
```

**Output**

```
0
2
4
6
8
10
```

## Break Statement

The break statement can also be used to jump out of a loop.

This example jumps out of the loop when i is equal to 4:

**Example**

```
    for (int i = 0; i < 10; i++) {
      if (i == 4) {
        break;
    }
      System.out.println(i);
    }
```

**Output**

```
0
1
2
3
```

## Continue Example

**Example**

```
    int i = 0;
    while (i < 10) {
      if (i == 4) {
        i++;
        continue;
      }
      System.out.println(i);
      i++;
     }
```

**Output**

```
0
1
2
3
5
6
7
8
9
```

## Break Statement

The break statement can also be used to jump out of a loop.

This example jumps out of the loop when i is equal to 4:

**Example**

```
    for (int i = 0; i < 10; i++) {
      if (i == 4) {
        break;
    }
      System.out.println(i);
    }
```

**Output**

```
0
1
2
3
```

## Continue Example

**Example**

```
    int i = 0;
    while (i < 10) {
      if (i == 4) {
        i++;
        continue;
      }
      System.out.println(i);
      i++;
     }
```

**Output**

```
0
1
2
3
5
6
7
8
9
```

### Strings

Strings represent a sequence of characters.

**Example**

```
String name = "Masai School"
```

## String in-built functions

1. `String.length()`

This function is used to calculate the length of a string and the output is a int.

**Example**

```
String name = "Masai School";
int length = name.length();
System.out.println(length);
```

**Output**

```
12
```

1. `String.concat()`

This function is used to concatinate 2 strings , second string at the end of first string.

**Example**

```
String start = "Masai";
String end = "School";
String concat = start.concat(end);
System.out.println(concat);
```

**Output**

```
MasaiSchool
```

1. `string.split()`

This method is used to convert  a string to an array based on `regex` value.

**Example**

```

String name = "Masai School is Amazing";
String[] words = name.split(" ");  // Split based on space

for(String s : words){
System.out.println(s);
}
```

**Output**

```
Masai
School
is
Amazing
```

1. `String.toLowerCase()`

This method converts all the characters in a string to lower case.

**Example**

```
String name = "Masai";
System.out.println(name.toLowerCase());
```

**Output**

```
masai
```

1. `String.toUpperCase()`

This method converts all the characters to upper case.

**Example**

```
String name = "Masai";
System.out.println(name.toUpperCase());
```

**Output**

```
MASAI
```

1. `String.substring()`

This method gives a substring of a string

**Example 1**

```
        String name = "Masai School";
        String sub = name.substring(2, 12);
        System.out.println(sub);
```

**Output**

```
sai School
```

**Example 1**

```
        String name = "Masai School";
        String sub = name.substring(3);
        System.out.println(sub);
```

**Output**

```
ai School
```

# Java Arrays

Arrays are used to store multiple values in a single variable, instead of declaring separate variables for each value.

To declare an array, define the variable type with square brackets:

```
String[] cars;

```

We have now declared a variable that holds an array of strings. To 
insert values to it, we can use an array literal - place the values in a
 comma-separated list, inside curly braces:

**Example1**

```
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};

```

**Example2**

```
int[] myNum = {10, 20, 30, 40};

```

You can also create an array using the `new` keyword.

```
String[] name = new String[size];
```

Where size is the number of elements to be present

## Access the Elements of an Array:

You access an array element by referring to the index number.

**Example**

```
    String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
    System.out.println(cars[0]);
```

**Outputs**

```
Volvo

```

**Note:**

Array indexes start with 0: [0] is the first element. [1] is the second element, etc.

**Change an Array Element:**

To change the value of a specific element, refer to the index number:

**Example**

```
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
cars[0] = "Opel";
System.out.println(cars[0]);
```

**Now outputs Opel instead of Volvo**

**Array Length**

To find out how many elements an array has, use the length property:

**Example**

```
    String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
    System.out.println(cars.length);
```

**Output**

```
4
```

## Loop Through an Array

You can loop through the array elements with the for loop, and use 
the length property to specify how many times the loop should run.

## The following example outputs all elements in the cars array:

**Example**

```
    String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
     for (int i = 0; i < cars.length; i++) {
      System.out.println(cars[i]);
}

```

**Output**

```
Volvo
BMW
Ford
Mazda
```
