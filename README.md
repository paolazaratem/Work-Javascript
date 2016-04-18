# Work-Javascript
Javascript love me &lt;3

A computer program is a list of "instructions" to be "executed" by the computer.
In a programming language, these program instructions are called statements.
JavaScript is a programming language.
JavaScript statements are separated by semicolons.
JavaScript has two types of values: fixed and variable values.
Fixed values are called literals. Variables values are called variables.

**literals**
Numbers:
10.5
150

Strings: written with double or single quotes.
'Hello'
"World"

**Variables**
Variales are use to store data values.
Use the ´var´ keyword to declare variables.
And equal sign ´=´ is used to assign Variables.

example:
var num; //num is a variable
num = 16 ; // x is assigned the value 16

**Expresions**
An Expresion is a combination of values, variables and operators has a result to value.
The computation is a called an evaluation.

Example:
40/2 = 20
var x ;
x * 10 ;

comments:
//asasas
/* apskskaskaosas */

Identifiers= name variables
the first character must be a letter, an underscore (_), or a dollar sign ($).

**Javascript is case sensitive**
the next variables are different
lastName = "Doe";
lastname = "Peterson";

Put name the Identifiers:
hyphens: put-name
underscore: put-name
Camel Case: putName

in javascript:
- JavaScript doesn´t interpret Var or VAR, the keyword correct is var.
- is often use the camel case: firstName, lastName
- hyphens aren't allow in javascript. It's reserved for the subtract.
- the statements are executed in the same order as they are written.

GOOD PRACTICE:
Put space between operators or assignations, the code is more readable.
var x = y + z;

statements are instructions to be executed by the web browser.
semicolons separate statements
comments can be used to explain JavaScript code, and to make it more readable.
The "equal to" operator is written like == in JavaScript.
add semicolon in the end of statement:
a = 5;
b = 6;
c = a + b;

As with algebra, you can do arithmetic with JavaScript variables, using operators like = and +:
Example
var x = 5 + 2 + 3;

If you add a number to a string, the number will be treated as string, and concatenated.
var x = "5" + 2 + 3; // x = 523;


NOTES:

JavaScript can "display" data in different ways:
Writing into an alert box, using window.alert().
Writing into the HTML output using document.write().
Writing into an HTML element, using innerHTML.
Writing into the browser console, using console.log().


Keyword 	Description
break 	Terminates a switch or a loop
continue 	Jumps out of a loop and starts at the top
debugger 	Stops the execution of JavaScript, and calls (if available) the debugging function
do ... while 	Executes a block of statements, and repeats the block, while a condition is true
for 	Marks a block of statements to be executed, as long as a condition is true
function 	Declares a function
if ... else 	Marks a block of statements to be executed, depending on a condition
return 	Exits a function
switch 	Marks a block of statements to be executed, depending on different cases
try ... catch 	Implements error handling to a block of statements
var 	Declares a variable
