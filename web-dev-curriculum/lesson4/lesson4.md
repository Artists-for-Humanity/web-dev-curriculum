# 🏆  **Goals:** 
- ⭐️ learn the basics of javascript

<br>

# JavaScript Basics
<p style="text-align: center;">
JavaScript is a programming language that is commonly used to create interactive websites. In this guide, we will cover the basics of JavaScript, including variables, data types, operators, functions, objects, loops, and conditional statements. </p>


# ➡️ Variables
<span style="text-decoration:underline"> Variables</span> are used to store values in JavaScript. In order to create a variable, you must first declare it using the var, let,  or const keyword, followed by the variable name. You can then assign a value to the variable using the assignment  <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">=</span> operator

``` javascript
var placeholder = True;
let myVariable = "Hello, world!";
const PI = 3.14;
```

# ➡️ Data Types
JavaScript supports several different data types, including strings, numbers, booleans, null, and undefined. You can use the <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">typeof</span> function to determine the data type of a variable.

``` javascript
let myString = "Hello, world!";
let myNumber = 42;
let myBoolean = true;
let myNull = null;
let myUndefined = undefined;

console.log(typeof myString); // outputs "string"
console.log(typeof myNumber); // outputs "number"
console.log(typeof myBoolean); // outputs "boolean"
console.log(typeof myNull); // outputs "object"
console.log(typeof myUndefined); // outputs "undefined"
```

# ➡️ Operators
JavaScript supports several different operators, including arithmetic operators, comparison operators, and logical operators. These can be used to perform mathematical operations, compare values, and combine multiple conditions.

``` javascript
let x = 10;
let y = 5;

console.log(x + y); // outputs 15
console.log(x - y); // outputs 5
console.log(x * y); // outputs 50
console.log(x / y); // outputs 2
console.log(x % y); // outputs 0

console.log(x == y); // outputs false
console.log(x != y); // outputs true
console.log(x > y); // outputs true
console.log(x < y); // outputs false
console.log(x >= y); // outputs true
console.log(x <= y); // outputs false

console.log(x > 0 && y > 0); // outputs true
console.log(x > 0 || y < 0); // outputs true
console.log(!(x > 0)); // outputs false
```


# ➡️ Functions
Functions are reusable blocks of code that can be called multiple times throughout your program. You can define a function using the function keyword, followed by the function name and any parameters that the function requires. You can then call the function by its name, passing in any required arguments.

``` javascript
function greet(name) {
    console.log(`Hello, ${name}!`);
  }
  
  greet("John"); // outputs "Hello, John!"
  greet("Jane"); // outputs "Hello, Jane!"

```
# ➡️ Objects
Objects are used to represent complex data structures in JavaScript. An object is created using curly braces {}, and can contain one or more key-value pairs.

``` javascript
let person = {
    name: "John",
    age: 30,
    city: "New York"
  };
  
  console.log(person.name); // outputs "John"
  console.log(person.age); // outputs 30
  console.log(person.city); // outputs "New York"
```

# ➡️ Loops
Loops are used to execute a block of code multiple times. JavaScript supports several different types of loops, including for loops, while loops, and do-while loops.

``` javascript
// for loop
for (let i = 0; i < 5; i++) {
  console.log(i);
}

// while loop
let i = 0;
while (i < 5) {
  console
}
```