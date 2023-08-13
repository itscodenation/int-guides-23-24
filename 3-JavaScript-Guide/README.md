# JavaScript Fundamentals Guide

## Table of Contents
1. [Variable Syntax](#variable-syntax)
2. [Input and `.value`](#input-and-value)
3. [Data Types and Data Structures](#data-types-and-data-structures)
4. [Methods](#methods)
5. [Concatenation](#concatenation)
6. [Mathematical Operators](#mathematical-operators)
7. [DOM Manipulation](#dom-manipulation)
8. [Event Handlers](#event-handlers)
9. [Conditionals](#conditionals)
10. [Comparison Operators](#comparison-operators)
11. [Logical Operators](#logical-operators)
12. [Arrays and Loops](#arrays-and-loops)
13. [`.insertAdjacentHTML`](#insertAdjacentHTML)

### Variable Syntax
You can declare and assign values to variables using `let`, `const`, or `var`. `let` is preferred when the value may change, while `const` is used for unchangeable values.

```javascript
let faveSeason = "summer"; // Declares a variable and gives it the name, faveSeason
faveSeason = "autumn"; // Assigns a different value to the variable faveSeason
let coldSeason = "winter"; // Declares a variable named coldSeason and assigns it a value "winter"
```

### Input and `.value`
You can obtain values from HTML input fields using `.value` in JavaScript.

```html
<input class="username">
<button class="login">Go!</button>
```
```javascript
button.onclick = function() {
  let name = document.querySelector('.username').value; // Retrieves the value from the input field
};
```

### Data Types and Data Structures
JavaScript has several primitive data types, including numbers, strings, and boolean values. Also, arrays are objects that store multiple values.

```javascript
let temperature = -1; 
let greeting = "Joliz is here!";
let space = '    ';
let oddNumbers = [1, 3, 5, 7, 9];
```

### Methods
JavaScript provides various built-in methods to perform actions, such as logging to the console, alerting, and converting data types.

```javascript
console.log("Test"); // Logs "Test" to the console
alert("Password error!"); // Displays a pop-up alert box
let year = "2015"; 
Number(year); // Converts "2015" into the number 2015
```

### Concatenation
You can join together or concatenate strings in JavaScript using the `+` operator.

```javascript
let userName = "codeNationStudent";
userList.insertAdjacentHTML("beforebegin", "<li> Hello " + userName + "</li>");
```

### Mathematical Operators
JavaScript provides arithmetic operators such as addition, subtraction, multiplication, and division.

```javascript
let a = 5, b = 3;
let sum = a + b; // Addition
let difference = a - b; // Subtraction
let product = a * b; // Multiplication
let quotient = a / b; // Division
```

### DOM Manipulation
The Document Object Model (DOM) allows you to interact with and modify HTML content from JavaScript.

```javascript
let paragraph = document.querySelector("p");
paragraph.innerHTML = "Hello!"; // Changes the text inside a <p> tag
```

### Event Handlers
You can define event handlers to respond to user actions like clicks, key presses, etc.

```javascript
button.onclick = function() {
   button.style = "color: blue"; // Changes the button text color to blue
};
```

### Conditionals
JavaScript provides conditional statements like `if`, `else if`, and `else` to control the flow of your program.

```javascript
let num = 11;
if (num < 5) {
  console.log("Less than 5");
} else if (num < 10) {
  console.log("Less than 10");
} else {
  console.log("Greater than 10");
}
```

### Comparison Operators
Comparison operators like `<`, `>`, `<=`, `>=`, `==`, and `===` allow you to compare values.

```javascript
if (number < 10) {
  // ...
} else if (grade > 70) {
  // ...
}
```

### Logical Operators
Logical operators like `&&`, `||`, and `!` allow you to create complex logical expressions.

```javascript
if (age > 16 && passedTest === true) {
  console.log("you can drive.");
} else {
  console.log("no driving yet.");
}
```

### Arrays and Loops
Arrays store multiple values, and loops allow you to iterate through these values.

```javascript
let classNames = ["English", "History", "Calculus"];
let arrayLength = classNames.length; // Returns 3
let newClass = "AP CS";
classNames.push(newClass); // Adds "AP CS" to the array

for (let arrayElement of classNames) {
  // loop body goes here
}
```

### `.insertAdjacentHTML`
This method allows you to insert HTML into the DOM at a specified position.

```javascript
let groceries = ["Lettuce", "Tomatoes", "Milk"];
ul.insertAdjacentHTML("beforebegin", "<li>" + groceries[2] + "</li>");
```
