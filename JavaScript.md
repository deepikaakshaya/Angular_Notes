# JavaScript
## Introduction
* JavaScript is the programming language of the Web.
*  Browser specification of javascript language --->ECMAScript or ES6
* javascript server runtime used to run javascript language everywhere
* JS code run in browser
* JavaScript accepts both double and single quotes
*  JavaScript Can Change HTML Content
* JavaScript is the default scripting language in HTML
* In HTML, JavaScript code is inserted between `<script>` and `</script>` tags

## Primitive Types
* strings
* numbers
* boolean
* undefined
* null
### Dynamic typing
* Runtime based changes in js by declaring
## DOM
* Document object model, the document object the browser creates when it is renders an HTML documents
*  JavaScript HTML methods is `getElementById()`.

## JavaScript Keywords
* JavaScript keywords are reserved words. Reserved words cannot be used as names for variables.
* *break*
	- Terminates a switch or a loop
* * continue*
--->Jumps out of a loop and starts at the top
* *debugger*
--->Stops the execution of JavaScript, and calls (if available) the debugging function
* *do ... while*
---> Executes a block of statements, and repeats the block, while a condition is true
* *for*
---> A block of statements to be executed, as long as a condition is true
* *function*
---> Declares a function
* *if ... else*
	- Marks a block of statements to be executed, depending on a condition
* *return*
	- Exits a function
* *switch*
	- Marks a block of statements to be executed, depending on different cases
* *try ... catch*
	- Implements error handling to a block of statements
* *var*
	- Declares a variable


## JavaScript Values
*  JavaScript ignores multiple spaces. You can add white space to your script to make it more readable.
* The JavaScript syntax defines two types of values:
	-   Fixed values
	-   Variable values
- Fixed values are called **Literals**
- Variable values are called **Variables**
 
## JS Function 
*  JavaScript function is a block of code designed to perform a particular task
*  A JavaScript function is executed when "something" invokes it (calls it)
*  A JavaScript `function` does not perform any checking on parameter values (arguments) and it is a block of JavaScript code, that can be executed when "called" 
*  For example, a function can be called when an **event** occurs, like when the user clicks a button
*  JavaScript can "display" data in different ways
*  Writing into an HTML element, using `innerHTML`
*  Writing into the HTML output using `document.write()`
*  Writing into an alert box, using `window.alert()`
*  Writing into the browser console, using `console.log()`
```
function _name_(_parameter1, parameter2, parameter3_) {  
 // _code to be executed_  
}
```
* You can reuse code: Define the code once, and use it many times
* You can use the same code many times with different arguments, to produce different results


##  JS statements 
*  Values, Operators, Expressions, Keywords, and Comments.
*  Identifiers are used to name variables 
*  JavaScript comments can be used to explain JavaScript code, and to make it more readable also be used to prevent execution, when testing alternative code.
*  There are 3 ways to declare a JavaScript variable:
	     Using `var` ,  Using `let` ,  Using `const`
* var pi = 3.14;  var person = "John Doe";  var answer = 'Yes I am!';
* The `let` keyword was introduced in [ES6 (2015)]
* Variables defined with `let` cannot be Redeclared.
* Variables defined with `let` must be Declared before use.
* Variables defined with `let` have Block Scope.
* Variables declared within a JavaScript function, become **LOCAL** to the function.
* Local variables can only be accessed from within the function.

## Block Scope
* Before ES6 (2015), JavaScript had only **Global Scope** and **Function Scope**
* ES6 introduced two important new JavaScript keywords: `let` and `const`
* These two keywords provide **Block Scope** in JavaScript.
* Variables declared inside a { } block cannot be accessed from outside the block
* The `const` keyword was introduced in [ES6 (2015)]
* Variables defined with `const` cannot be Redeclared
* Variables defined with `const` cannot be Reassigned
* Variables defined with `const` have Block Scope
* Always use `const` when you declare:
-   A new Array
-   A new Object
-   A new Function
-   A new RegExp

## JavaScript Assignment Operators
* Assignment operators assign values to JavaScript variables.
* Operator with example
```
=

x = y

x = y

+=

x += y

x = x + y

-=

x -= y

x = x - y

*=

x *= y

x = x * y

/=

x /= y

x = x / y

%=

x %= y

x = x % y

**=

x **= y

x = x ** y
```

## Accessing Object Properties
* You can access object properties in two ways:
```
_objectName.propertyName		 _or        _objectName["propertyName"]_
```
* The **name:values** pairs in JavaScript objects are called **properties**
* JavaScript has only one type of number. Numbers can be written with or without decimals.
* JavaScript arrays are used to store multiple values in a single variable.

## JS Events
* HTML events are **"things"** that happen to HTML elements
* When JavaScript is used in HTML pages, JavaScript can **"react"** on these events
```
onchange

An HTML element has been changed

onclick

The user clicks an HTML element

onmouseover

The user moves the mouse over an HTML element

onmouseout

The user moves the mouse away from an HTML element

onkeydown

The user pushes a keyboard key

onload

The browser has finished loading the page
```

## Extracting String Parts
* String methods help you to work with strings
* There are 3 methods for extracting a part of a string
-   `slice(_start_, _end_)`
-   `substring(_start_, _end_)`
-   `substr(_start_, _length_)`
* A string is converted to upper case with `toUpperCase()`
* A string is converted to lower case with `toLowerCase()`
* `concat()` joins two or more strings
* The `trim()` method removes whitespace from both sides of a string
* The `charAt()` method returns the character at a specified index (position) in a string
* JavaScript methods for searching strings:
```
-   String.indexOf()
-   String.lastindexOf()
-   String.startsWith()
-   String.endsWithf()

```

