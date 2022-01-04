1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let percentage = function (marks, total) {
  return (marks * 100) / total;
}

let percentage = (marks, total) => {
  return (marks * 100) / total;
}

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Function Decleration
// Your answer
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
// Function Expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
// Fuction Expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
// Function Expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;
// Function Expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

When the function is started with the keyword function that kind of function is known as function decleration.
Ex- 
```js
function add(numA, numB){
return numA + numB
}
```
Function expression is store a function inside a variable as an expression.
Ex-
```js
const addNumbers = function add(numA, numB){
return numA + numB
}
```

4. Why is a function call an expression in JavaScript?

As function is an object in JavaScript. Thus, if a function is stored in a variable in an expression form it's known as function expression.

Function Expression is exist in JavaScript because function are object and objects are values.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Valid (because the function called with parameters)
five = add; // Valid (because the function is not called with parameters, it's a function reference)
five = five(10, 11); // Valid (because the function is called with parameters, also the variable five is already declared to store the value)
five = function () {
five = function () {
  return 'Hello';
}; // Valid (because it is a function expression)
```

6. What is the difference between function definition and function call? Explain with an example.

Function defination is when we define a function and function call is when we execute the function.

Ex-
```js
function add (num1, num2) {
  return num1 + num2;
} // Function Defination

add (2,6); // Function call
```

7. What is the similarities between function definition and function call?

Similarty is execution of a function.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid (because function is an object in JavaScript)
```

9. What is higher order function explain with an example.

When a function defination is been passed but not a function call inside another function it is a higher order function.



10. Explain what is callback function. Why you can pass a function inside a function?

A function that is passed a a parameter to a higher order function is known as a callback function. As function is an object in JavaScript and object is an expression, thus, a function can be passed inside a function.
