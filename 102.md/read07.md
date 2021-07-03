# read07
# Expressions and operators
# Operators
## JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

## 1- Assignment operators
## 2- Comparison operators
## 3- Arithmetic operators
## 4- Bitwise operators
## 5- Logical operators
## 6- String operators
## 7- Conditional (ternary) operator
## 8- Comma operator
## 9- Unary operators
## 10- Relational operators

# ![](https://media.geeksforgeeks.org/wp-content/uploads/Operators.png)

# ![](https://media.geeksforgeeks.org/wp-content/uploads/20190708164646/Operators-Associativity-1.jpg)
# ![](https://i1.wp.com/w3processing.com/java/images/operators.png)
# Functions :
##  building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output.
# Defining functions
## function keyword, followed by:

## The name of the function.
## A list of parameters to the function, enclosed in parentheses and separated by commas.
## The JavaScript statements that define the function, enclosed in curly brackets, {...}.
## ![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/03/JavaScript-function-tutorial.jpg)

# Function scope:
## Variables defined inside a function cannot be accessed from anywhere outside the function, because the variable is defined only in the scope of the function. However, a function can access all variables and functions defined inside the scope in which it is defined.

## In other words, a function defined in the global scope can access all variables defined in the global scope. A function defined inside another function can also access all variables defined in its parent function, and any other variables to which the parent function has access.
# Predefined functions
## JavaScript has several top-level, built-in functions:

## eval
## The eval method evaluates JavaScript code represented as a string.

## uneval
## The uneval method creates a string representation of the source code of an Object.

## isFinite
## The global isFinite() function determines whether the passed value is a finite number. If needed, the parameter is first converted to a number.

## isNaN
## The isNaN function determines whether a value is NaN or not. Note: coercion inside the isNaN function has interesting rules; you may alternatively want to use Number.isNaN(), as defined in ECMAScript 2015, or you can use typeof to determine if the value is Not-A-Number.

## parseFloat
## The parseFloat function parses a string argument and returns a floating point number.

## parseInt
## The parseInt function parses a string argument and returns an integer of the specified radix (the base in mathematical numeral systems).

## decodeURI
## The decodeURI() function decodes a Uniform Resource Identifier (URI) previously created by encodeURI or by a similar routine.

## decodeURIComponent
## The decodeURIComponent method decodes a Uniform Resource 
## Identifier (URI) component previously created by encodeURIComponent or by a similar routine.

## encodeURI
## The encodeURI method encodes a Uniform Resource Identifier (URI) by replacing each instance of certain characters by one, two, three, or four escape sequences representing the UTF-8 encoding of the character (will only be four escape sequences for characters composed of two "surrogate" characters).

## encodeURIComponent
## The encodeURIComponent method encodes a Uniform Resource Identifier (URI) component by replacing each instance of certain characters by one, two, three, or four escape sequences representing the UTF-8 encoding of the character (will only be four escape sequences for characters composed of two "surrogate" characters).

## escape
## The deprecated escape method computes a new string in which certain characters have been replaced by a hexadecimal escape sequence. Use encodeURI or encodeURIComponent instead.

## unescape
## The deprecated unescape method computes a new string in which hexadecimal escape sequences are replaced with the character that it represents. The escape sequences might be introduced by a function like escape. Because unescape is deprecated, use decodeURI or decodeURIComponent instead.
