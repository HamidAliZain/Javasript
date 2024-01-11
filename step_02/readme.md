# Function

In JavaScript, functions are blocks of reusable code that can be defined and called to perform a specific task. Here's a basic overview of how to declare and use functions in JavaScript:

## Function Declaration

You can declare a function using the function keyword, followed by the function name, parameters (if any), and the function body.

```javascript
function sayHello() {
  console.log("Hello, world!");
}

// Function with parameters
function greet(name) {
  console.log("Hello, " + name + "!");
}
```

## Function Call

After declaring a function, you can call it by using its name followed by parentheses.

```javascript
sayHello(); // Outputs: Hello, world!
greet("John"); // Outputs: Hello, John!
```

## Return Statement:

Functions can also return values using the return statement.

```javascript
function add(a, b) {
  return a + b;
}

var result = add(3, 5);
console.log(result); // Outputs: 8
```

## Function Expressions:

Arrow functions provide a concise syntax for writing functions, especially when the function body is a single expression.

```javascript
var square = (num) => num * num;
console.log(square(3)); // Outputs: 9
```

## Anonymous Functions:

Functions without a name are called anonymous functions and are often used as arguments to other functions

```javascript
var numbers = [1, 2, 3];

numbers.forEach(function (num) {
  console.log(num);
});
```
