## If Statement

The "if-else" statement in JavaScript is used for conditional branching. It allows you to execute different blocks of code depending on whether a specified condition evaluates to true or false

```javascript
var x = 10;

if (x > 5) {
  console.log("x is greater than 5");
}
```

In this example, the code inside the curly braces will only execute if the condition x > 5 is true. If the condition is false, the code inside the block will be skipped.

### another example

```javascript
var age = 18;

if (age >= 18) {
  console.log("you are 18 plus");
}
```

In this example, the code inside the curly braces will only execute if the condition age >= 18 is true. If the condition is false, the code inside the block will be skipped.

## If-Else Statement:

```javascript
var x = 10;
var y = 3;

if (y > 5) {
  console.log("y is greater than 5");
} else {
  console.log("y is not greater than 5");
}
```

Here, if y > 5 is true, the first block of code will execute; otherwise, the block inside the else will execute.

## If-Else Else-If Statement:

```javascript
var z = 7;

if (z > 10) {
  console.log("z is greater than 10");
} else if (z > 5) {
  console.log("z is greater than 5 but not 10");
} else {
  console.log("z is 5 or less");
}
```

This structure allows you to check multiple conditions in sequence. If the first condition is false, it moves on to the next else if condition, and so on. If none of the conditions are true, the code inside the else block will execute.
