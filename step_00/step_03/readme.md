# Operator

Operators in JavaScript are symbols or keywords that perform operations on operands. Operands can be variables, values, or expressions. JavaScript supports various types of operators, including arithmetic, comparison, logical, assignment, and more. Here's an overview of the main types of operators in JavaScript

## Addition

The addition operator (+) is used to add two values. In this case, it adds the values 5 and 3, resulting in the sum variable holding the value 8.

```javascript
var sum = 5 + 3;
```

## Subtraction (-)

The subtraction operator (-) is used to subtract the right operand from the left operand. Here, it subtracts 5 from 10, and the sub variable holds the result, which is 5.

```javascript
var sub = 10 - 5; // 5
```

## Multiplication (\*)

The multiplication operator (\*) is used to multiply two values. In this example, it multiplies 3 by 7, and the product variable holds the result, which is 21.

```javascript
var product = 3 * 7; // 21
```

## Division (/):

The division operator (/) is used to divide the left operand by the right operand. In this case, it divides 15 by 3, and the quotient variable holds the result, which is 5.

```javascript
var quotient = 15 / 3; // 5
```

## Remainder (%)

The remainder operator (%) returns the remainder of the division of the left operand by the right operand. In this example, it calculates the remainder when 10 is divided by 3, and the remainder variable holds the result, which is 1.

```javascript
var remainder = 10 % 3; // 1
```

# Comparison Operators:

## Equal (==)

The equal operator (==) performs loose equality, converting operands to the same type before making the comparison. In this case, it returns true because the numeric value 5 is considered equal to the string value "5" after type coercion.

```javascript
var isEqual = 5 == "5"; // true (loose equality)
```

## Strict Equal (===):

The strict equal operator (===) performs strict equality without type coercion. It returns false because the operands have different types (number and string).

```javascript
var isStrictEqual = 5 === "5"; // false (strict equality)
```

## Not Equal (!=):

The not equal operator (!=) performs loose inequality. It returns true because 10 is not equal to 8.

```javascript
var isNotEqual = 10 != 8; // true
```

## Strict Not Equal (!==):

The strict not equal operator (!==) performs strict inequality without type coercion. It returns true because 10 and "10" are of different types.

```javascript
var isStrictNotEqual = 10 !== "10"; // true
```

# Greater Than (>), Less Than (<), Greater Than or Equal (>=), Less Than or Equal (<=):

These operators (>, <, >=, <=) perform standard numeric comparisons, resulting in boolean values (true or false).

```javascript
var greater = 10 > 5; // true
var less = 8 < 3; // false
var greaterOrEqual = 7 >= 7; // true
var lessOrEqual = 5 <= 2; // false
```

# Logical Operators:

## AND (&&):

The logical AND operator (&&) returns true if both operands are true, otherwise false. In this case, it evaluates to false

```javascript
var result = true && false; // false
```

## OR (||):

The logical OR operator (||) returns true if at least one of the operands is true. In this case, it evaluates to true.

```javascript
var result2 = true || false; // true
```

# Assignment Operators:

## Addition Assignment (+=):

The addition assignment operator (+=) adds the right operand to the left operand and assigns the result to the left operand.

```javascript
var y = 5;
y += 3; // y is now 8
```

## Conditional (Ternary) Operator (? :):

```javascript
var age = 20;
var status = age >= 18 ? "Adult" : "Minor";
```

The conditional (ternary) operator is a concise way of writing an if-else statement. In this example:

If the condition age >= 18 is true, then the value of the status variable is set to "Adult".
If the condition age >= 18 is false, then the value of the status variable is set to "Minor".
This single line of code is equivalent to the following if-else statement:

```javascript
var age = 20;
var status;

if (age >= 18) {
  status = "Adult";
} else {
  status = "Minor";
}
```
