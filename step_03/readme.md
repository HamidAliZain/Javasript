# Array Methods
# Adding and Removing Elements:
## push

push(): Adds one or more elements to the end of an array and returns the new length of the array.

```javascript
let fruits = ["apple", "banana", "orange"];
fruits.push("kiwi");
```

## pop

pop(): Removes the last element from an array and returns that element.

```javascript
let fruits = ["apple", "banana", "orange"];
let removed = fruits.pop("orange"); // 'orange'
```

## unshift

unshift(): Adds one or more elements to the beginning of an array and returns the new length of the array.

```javascript
let fruits = ["apple", "banana", "orange"];
fruits.unshift("kiwi");
```

## shift

shift(): Removes the first element from an array and returns that element.

```javascript
let fruits = ["apple", "banana", "orange"];
let removed = fruits.shift("apple"); // 'apple'
```

# Modifying Arrays:

## splice

splice(): Adds or removes elements from an array at a specified index.

```javascript
let fruits = ["apple", "banana", "orange"];
fruits.splice(1, 1, "grape", "kiwi"); // Removes 'banana' and adds 'grape', 'kiwi'
```

# Accessing Elements:

## slice

slice(): Returns a shallow copy of a portion of an array into a new array object selected from start to end.

```javascript
let fruits = ["apple", "banana", "orange", "grape", "kiwi"];
let selectedFruits = fruits.slice(1, 3); // Returns ['banana', 'orange']
```

# Searching and Filtering:

## indexOf

indexOf(): Returns the first index at which a given element can be found in the array, or -1 if it is not present.

```javascript
let fruits = ["apple", "banana", "orange", "grape", "kiwi"];
let index = fruits.indexOf("orange"); // Returns 2
```

## filter

filter(): Creates a new array with all elements that pass the test implemented by the provided function.

```javascript
let numbers = [1, 2, 3, 4, 5];
let evenNumbers = numbers.filter((num) => num % 2 === 0); // Returns [2, 4]
```

# Iterating over Arrays:

## forEach

forEach(): Executes a provided function once for each array element.

```javascript
let numbers = [1, 2, 3, 4, 5];
numbers.forEach((num) => console.log(num * 2)); // Logs doubled values
```

## map

map(): Creates a new array populated with the results of calling a provided function on every element in the calling array.

```javascript
let numbers = [1, 2, 3, 4, 5];
let doubled = numbers.map((num) => num * 2); // Returns [2, 4, 6, 8, 10]
```
