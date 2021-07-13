# Typescript
* Superset of javascript that compiles to plain javascript
* object oriented with classes, interfaces etc..
* Compiled to Js, both on server side & client side
* It is start with JS and end with JS
* .js file can be renamed to .ts
## Benefits
* compilation ---> Typescript will compile code & generate compilation errors, if it find some sort of syntax error 
* Strong static typing ---> JS is not strong typed. Typescript had through the TLS (Typescript Language Service)
* TS support Type definitions---> for existing libraries (JS)
* .d .ts extension provides definition for external JS libraries
## Component of TS
1. Language = comprise of syntax, keywords & type annotations
2. Compiler = convert instruction written in TS to JS
3.  Language Services = Compiler pipeline (editor application) supports editor operations, statement completions etc..
### Text Editor
* you can write in text editor
* save as .ts file extension
### TS compiler
* app.ts---> tsc_app.ts--->app.js
* here tsc_app.ts is a typescript compiler or transcompiler/transpiler
* source to source compiler
* tsconfig.json---> TS config object is just json object with config values
## To install typescript
``npm install -g typescript``
* the above syntax is used to install TS
* TS has modules, functions, variable, statement, expressions and comments
* Console --->refer to terminal window
* log()--->function to display text
* Compile= ``tsc test.ts``
* Run = ``node test.js``
* multiple files can be compiled at once
* eg : tsc test1.ts, test2.ts, test3.ts
## Compiler Flag
* ``--help`` --->Display help manual
* ``--module`` --->Load external module
* ``--target`` --->set the target ECMA version
* ``--declararion`` --->Generate an additional .d.ts file
* ``--removeComments`` --->Removes all comments from the Output file
*  ``--out`` --->Compile multiple files into a single output file
*  ``--sourcemap`` --->generate a sourcemap(.map) file
*  ``--module noImplicitAny`` --->Disallows the compiler from inferring the any type
*  ``--watch`` --->Watch for file changes and recompile them on the fly
## Build-In-Types
* number
* string
* boolean
* void
* null
* undefined
## Declaring variable
* var [identifier] : [type-annotation] = value;
* var [identifier] : [type-annotation] ;
* var [identifier]  = value;
* var [identifier] ;
## Loops
* Definite loop 
			--->for
* Indefinite loop
			---> while, do while
* Break ---> Take the control out of the construct and exit the loop
* continue--->skips the statement in current iteration & takes the control back to the begining of the loop
#### Parameterized function
* **Call by value** ---> copies value of an argument into formal parameter
*  **Call by pointer** --->copies the address of an argument into formal parameter
#### Function Overoad
* function have the capability to operate differently on the basis of the input provided to them
* ``function display (string) : void ;``
* ``function display (s : string , n : number ) : void ;``
* function signature doesn't include the functions return type
#### Number methods
* toExponential()
* toFixed()
* toLocaleString()
## Tuple operation
* Tuple in typescript supports various operation like pushing a new item, removing an item from the tuple
## Union
 * union types are a powerful way to express a value that can be one of the several types
 * two or more data types are combined using the pipe ( | ) symbol
 * ```
 		var v : string | number
 		v = 12 
		console.log("number" + v);
		function display (name :string | string []){ }```
## Interface
* Syntactical contract that an entity should conform
* define properties , methods & events which are the members of the interface
* interfaces can't be converted to javascript
* Interface can define both kind of key an array uses and the type of entry it contains
## Classes
* Typescript is object oriented javascript
* class in terms of OOP is a blueprint for creating objects
* JS ES5 didn't support classes
* fields---> data pertaining to objects
* constructor ---> allocating memory for objects of the class
* Functions ---> action an object can take
### Static keyword
* can be applied to data members of a class
### Data hiding
* Class can control the visibility of its data members to members of other classes
* Encapsulation needed --->access modifier
## Ambient
* way of telling the TS compiler that actual source code exists elsewhere
* ambient declaration help to seamlessly integrate other JS libraries into typescript
## Generic
* create functions and classes
* reused and reduce duplicated code into single generic function
## Module
* They encourage more explicit dependencies
## TS library files
* type information ---> .d.ts
* source map---> contain metadata of TS
* Browser---> only do parsing and downloading data
## Reference
* typescriptlang.org