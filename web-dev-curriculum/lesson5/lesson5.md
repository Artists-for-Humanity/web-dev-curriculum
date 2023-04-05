# JavaScript Loops and Advanced Concepts
##In this lesson, we will cover more advanced JavaScript concepts, including different types of loops, control statements, and functions.

# Loops
Loops are used to execute a block of code multiple times. JavaScript supports several different types of loops:

# For Loop
The for loop is used to execute a block of code a specific number of times. It consists of three parts:

- Initialization: initialize a counter variable to start the loop.
- Condition: the loop will continue to execute as long as this condition is true.
- Update: this will be executed at the end of each iteration, usually to increment or decrement the counter variable.

```
for (let i = 0; i < 10; i++) {
  console.log(i);
}
```
<br>

# While Loop
The while loop is used to execute a block of code as long as a specified condition is true.

```
let i = 0;
while (i < 10) {
  console.log(i);
  i++;
}
```

# Do-While Loop
The do-while loop is similar to the while loop, but the code will be executed at least once, regardless of whether the condition is true or false.

```
let i = 0;
do {
  console.log(i);
  i++;
} while (i < 10);
```

# Control Statements
Control statements are used to control the flow of a program, and include if statements, switch statements, and the ternary operator.

## If Statement
The if statement is used to execute a block of code if a specified condition is true.

```
let x = 10;
if (x > 5) {
  console.log("x is greater than 5");
}
```

## Switch Statement
The switch statement is used to execute a block of code based on different cas

```
let day = "Monday";
switch (day) {
  case "Monday":
    console.log("Today is Monday");
    break;
  case "Tuesday":
    console.log("Today is Tuesday");
    break;
  default:
    console.log("Today is not Monday or Tuesday");
}
```
## Ternary Operator
The ternary operator is a shorthand way of writing an if statement that assigns a value based on a condition.

```
let x = 10;
let result = x > 5 ? "x is greater than 5" : "x is less than or equal to 5";
console.log(result);
```

# Functions
Functions are reusable blocks of code that can be called multiple times throughout your program. They can also take parameters and return values.

<br>

## Function Declaration
You can declare a function using the function keyword, followed by the function name and any parameters that the function requires.

```
function greet(name) {
  console.log(`Hello, ${name}!`);
}
```



