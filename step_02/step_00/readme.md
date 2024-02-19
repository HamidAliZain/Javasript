# Global Scope

Variables declared outside of any function have global scope.
They can be accessed from anywhere within the script, including inside functions.
Global variables are accessible from any function or block of code.

```javascript
var globalVariable = "I am global";

function myFunction() {
  console.log(globalVariable); // Output: I am global
}

myFunction(); // Function called
console.log(globalVariable); // Output: I am global
```

# Local Scope

Variables declared within a function have local scope.
They are only accessible within the function in which they are declared.
Variables with local scope cannot be accessed from outside of the function.

```javascript
function myFunction() {
  var localVariable = "I am local";
  console.log(localVariable); // Output: I am local
}

myFunction(); // Function called
console.log(localVariable); // Error: localVariable is not defined
```
