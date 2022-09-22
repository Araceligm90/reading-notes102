# Programming with JavaScript


### What is control flow?

The control flow is the order in which the computer executes statements in a script. 

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.


### Functions

Functions are one of the fundamental building blocks in JavaScript. It is very similar to a procedure -a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.


**Defining functions:**

Function declarations: a function declaration consists of the ‘function’ keyword, followed by:
The name of the function
A list of parameters to the function, enclosed in the parentheses and separated by commas.
The JS statements that define the function, enclosed in curly brackets.
Function expressions:these functions can be anonymous which means that do not have to have a name. However a name can be provided with the function expression. Providing a name allows the function to refer to itself, and also makes it easier to identify the function in a debugger’s stack traces. 

**Calling functions:**

Defining a function does not execute it. Defining only names the function and specifies what to do when the function is called. 

Calling the function actually performs the specified actions with the indicated parameters. For example, if you define the function ‘square’, you can call it as shown below:

        square(5);

The above calls the function with an argument of 5. When the function executes, it will return the value ‘25’.


**Function scope:**

Variables defined inside a function cannot be accessed from anywhere outside the function, because the variable is defined only in the scope of the function. 
