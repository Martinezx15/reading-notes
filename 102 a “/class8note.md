## **Expressions and operators**
      
A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. The following table describes the comparison operators in terms of this sample code:
Note: => is not a comparison operator but rather is the notation for Arrow functions.
 
## **Assignment operators**    
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

## **Assigning to properties**  
If an expression evaluates to an object, then the left-hand side of an assignment expression may make assignments to properties of that expression
If an expression does not evaluate to an object, then assignments to properties of that expression do not assign:
It is an error to assign values to unmodifiable properties or to properties of an expression without properties (null or undefined).
  
## **Destructuring**
For more complex assignments, the destructuring assignment syntax is a JavaScript expression that makes it possible to extract data from arrays or objects using a syntax that mirrors the construction of array and object literals.
  
## **Evaluation and nesting**
In general, assignments are used within a variable declaration (i.e., with const, let, or var) or as standalone statements)
However, like other expressions, assignment expressions like x = f() evaluate into a result value. Although this result value is usually not used, it can then be used by another expression.
Chaining assignments or nesting assignments in other expressions can result in surprising behavior. For this reason, some JavaScript style guides discourage chaining or nesting assignments). Nevertheless, assignment chaining and nesting may occur sometimes, so it is important to be able to understand how they work.
By chaining or nesting an assignment expression, its result can itself be assigned to another variable. It can be logged, it can be put inside an array literal or function call, and so on.
The evaluation result matches the expression to the right of the = sign in the "Meaning" column of the table above. That means that x = f() evaluates into whatever f()'s result is, x += f() evaluates into the resulting sum x + f(), x **= f() evaluates into the resulting power x ** y, and so on. 
 In the case of logical assignments, x &&= f(), x ||= f(), and x ??= f(), the return value is that of the logical operation without the assignment, so x && f(), x || f(), and x ?? f(), respectively.
When chaining these expressions without parentheses or other grouping operators like array literals, the assignment expressions are grouped right to left (they are right-associative), but they are evaluated left to right.
  
## **Loops and iteration**
## **for statement**
A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.
A for statement looks as follows: for ([initialExpression]; [conditionExpression]; [incrementExpression])statement
When a for loop executes, the following occurs: 
The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
- The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.
- If present, the update expression incrementExpression is executed.
- Control returns to Step 2.

 ## **while statement**
A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows: while (condition) statement
If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.
The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

 ## **Things I want to know more about*
- Arithmetic operators
- Bitwise operators
- Bitwise logical operators
- Bitwise shift operators
- Logical operators
- BigInt operators
  
