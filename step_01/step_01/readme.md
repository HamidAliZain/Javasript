# Loops

In JavaScript, loops are used to repeatedly execute a block of code until a certain condition is met. Loops are an essential part of control flow and help in automating repetitive tasks. There are different types of loops available in JavaScript, each serving a specific purpose.

## For Loop

The for loop is used when you know in advance how many times the code should be executed. It consists of three parts: initialization, condition, and iteration.

### Syntax

```javascript
for (initialization; condition; iteration) {
  // code to be repeated
}
```

### Example

```javascript
for (var i = 0; i < 5; i++) {
  console.log(i);
}
```

## While Loop

The while loop is used when the number of iterations is not known in advance, and the loop continues until a specified condition evaluates to false.

### Syntax

```javascript
while (condition) {
  // code to be repeated
}
```

### Example

```javascript
var count = 0;

while (count < 5) {
  console.log(count);
  count++;
}
```

## Do-While Loop

Similar to the while loop, the do-while loop executes the code block at least once before checking the condition. It continues to execute as long as the specified condition is true.

### Syntax

```javascript
do {
  // code to be repeated
} while (condition);
```

### Example

```javascript
var num = 1;

do {
  console.log(num);
  num++;
} while (num <= 5);
```

## for...in loop:

Used to iterate over the properties of an object. It enumerates the properties of an object, including inherited properties

### Example

```javascript
const person = { name: "John", age: 30, job: "developer" };

for (var key in person) {
  console.log(key, person[key]);
}
```

## for...of loop:

Introduced in ECMAScript 2015 (ES6), the for...of loop is used for iterating over iterable objects like arrays, strings, and more.

### Example

```javascript
const colors = ["red", "green", "blue"];

for (var color of colors) {
  console.log(color);
}
```

## forEach method:

For arrays, you can use the forEach method, which is a concise way to iterate over each element.

### Example

```javascript
const numbers = [1, 2, 3, 4, 5];

numbers.forEach(function (number) {
  console.log(number);
});
```
 