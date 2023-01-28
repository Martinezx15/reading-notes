# **Programming with JavaScript**
## **Control flowt**
The control flow is the order in which the computer executes statements in a script.
Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.
For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not: if (isEmpty(field)) { promptUser(); } else { submitForm();
A typical script in JavaScript or PHP (and the like) includes many control structures, including conditionals, loops and functions. Parts of a script may also be set to execute when events occur.
For example, the above excerpt might be inside a function that runs when the user clicks the Submit button for the form. The function could also include a loop, which iterates through all of the fields in the form, checking each one in turn. Looking back at the code in the if and else sections, the lines promptUser and submitForm could also be calls to other functions in the script. As you can see, control structures can dictate complex flows of processing even with only a few lines of code.
 
## **JavaScript Functions**
A JavaScript function is a block of code designed to perform a particular task.
A JavaScript function is executed when "something" invokes it (calls it). 
Example 
// Function to compute the product of p1 and p2
function myFunction(p1, p2) {
  return p1 * p2;
}

## **JavaScript Function Syntax**
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().
Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).
The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)
The code to be executed, by the function, is placed inside curly brackets: {}
Function parameters are listed inside the parentheses () in the function definition.
Function arguments are the values received by the function when it is invoked.
Inside the function, the arguments (the parameters) behave as local variables.

## **Function Invocation**
The code inside the function will execute when "something" invokes (calls) the function:
- When an event occurs (when a user clicks a button)
- When it is invoked (called) from JavaScript code
- Automatically (self invoked)
You will learn a lot more about function invocation later in this tutorial.

## **Function Return**
When JavaScript reaches a return statement, the function will stop executing.
If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.
Functions often compute a return value. The return value is "returned" back to the "caller":
Example Calculate the product of two numbers, and return the result:
let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}

## **Why Functions?**
You can reuse code: Define the code once, and use it many times.
You can use the same code many times with different arguments, to produce different results.
Example Convert Fahrenheit to Celsius: 
function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(77);

## **Functions Used as Variable Values**
Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.

Example Instead of using a variable to store the return value of a function:
let x = toCelsius(77);
let text = "The temperature is " + x + " Celsius";
You can use the function directly, as a variable value:
let text = "The temperature is " + toCelsius(77) + " Celsius";

## **Local Variables**
Variables declared within a JavaScript function, become LOCAL to the function.
Local variables can only be accessed from within the function. Example
// code here can NOT use carName

function myFunction() {
  let carName = "Volvo";
  // code here CAN use carName
}

// code here can NOT use carName

Since local variables are only recognized inside their functions, variables with the same name can be used in different functions.
Local variables are created when a function starts, and deleted when the function is completed.

## **JavaScript Objects**
### Real Life Objects, Properties, and Methods
 In real life, a car is an object
A car has properties like weight and color, and methods like start and stop:
let car = "Fiat";
Objects are variables too. But objects can contain many values.
This code assigns many values (Fiat, 500, white) to a variable named car:
const car = {type:"Fiat", model:"500", color:"white"};

##  **JavaScript Objects**
You have already learned that JavaScript variables are containers for data values.
This code assigns a simple value (Fiat) to a variable named car:

## **JavaScript reference**    
The JavaScript reference serves as a repository of facts about the JavaScript language. The entire language is described here in detail. As you write JavaScript code, you'll refer to these pages often (thus the title "JavaScript reference").
The JavaScript language is intended to be used within some larger environment, be it a browser, server-side scripts, or similar. For the most part, this reference attempts to be environment-agnostic and does not target a web browser environment.
If you are new to JavaScript, start with the guide. Once you have a firm grasp of the fundamentals, you can use the reference to get more details on individual objects and language constructs
## **Built-ins**
JavaScript standard built-in objects, along with their methods and properties.

## **Things I want to know more about**
- Inline JavaScript handlers
- Script loading strategies
- Internal JavaScript
- External JavaScript
- JavaScript running order
