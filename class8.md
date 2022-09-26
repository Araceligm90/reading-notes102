# Operators and Loops

## What are expressions and operators?


An expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

    - The expression x = 7 is an example of the first type. 
    This expression uses the '=' operator to assign the value 
    seven to the variable 'x'. 

    - The expression 3 + 4 is an example of the second type. 
    This expression uses the '+' operator to add 3 and 4 
    together and produce a value, 7. 


### Assignment operators

An assigment operator assigns a value to its left oeprand based on the value of the right operand. The simple assignment operator is equal (=).

### Comparison operators

A comparison opertor compares its operand and returns a logical value based on wheter the comparison is true. The operands an be numerical, string, logical or object values.

1. Equal (==): returns true if the operator are equal. 
2. Not equal (!=): returns true if the operands are not equal.
3. Strict equal (===): returns true if the oeprands are equal and of the same type.
4. Strict not equal (!==): returns true if the operands are of the same type but not equal, or are of different type.
5. Greater than (>): returns true if the left operand is greater than the right operand.
6. Greater than or equal (>=): returns true if the left operand is greater than or equal to the right operand.
7. Less than (<): returns true if the left operand is less than the right operand.
8. Less than or equal (<=): returns true if the lefr operand is less than or equal to the right operand.


## Loops

Loops offer and quick and easy way to do something repeatedly. There are mant kinds of loops, but they all essentually do the same: they repeat an action some number of times.

Today we are going to focud on two statements for loops provided in JavaScript:

### For statement:

A for loop repeats util a specific condition evaluates to false.

A for statement looks as follows:

    for (let i = 0; i < 5; i++){
        text += "The number is " + i + "<br>";
    }

From the example above, we can read:

- Expression 1 sets the variable before the loops start (let i = 0).
- Expression 2 defined the condition for the loop to run (i must be less than 5).
- Expression 3 increases a value (i++) each time the code block in the loop has been executed.

If we run the above code, we will see the below result:

    The number is 0
    The number is 1
    The number is 2
    The number is 3
    The number is 4


### While statement:

A while statement executes its statemets as long as a specific condition evaluates to true.

A while statement looks as follows:

    while ( i < 10) {
        text += "The number is " + 1;
        i++;
    }

In the above example we will see the below result: 

    The number is 0
    The number is 1
    The number is 2
    The number is 3
    The number is 4
    The number is 5
    The number is 6
    The number is 7
    The number is 8
    The number is 9

On the 10th loop the condition becomes false, therefore the satament within the loop stops executing.