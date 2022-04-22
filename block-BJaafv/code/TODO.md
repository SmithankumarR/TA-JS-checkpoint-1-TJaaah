1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
// here the first sum returns the actual value as an output
// second
function sum(a, b) {
  console.log(a + b);
}
// here in these function no return value as output only it displays the actual value of the experssion
```
2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`. 
 -----first = value; second = undefined ;

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
------- when you called sum function which returns the value of function by adding only parameters given total value will be 36 , because thirs parameter is not declared..

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
------ yes we can store the value because these returns the value hence by running add we can get the same output 
5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
function sayHello(name){
  return `hello Arya `;
}
sayHello()
6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage(); // hello john because username is global variable 
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); //  returns undifiend 

showMessage(); // "Hello, John"

alert(userName); // returns undifined
```

8. What is a Anonymous Function give example of three functions.
--- A function can be called without using function is called Anonymous function.. 
let hey = function (name) {
  return `hey ${name}`;
}
let bird = function (bird_name) {
  return ` The national bird of india  is ${bird-name}`;
}
let animal = function (animal_name) {
  return `The nationalanimal of india is ${animal_name}`;
}

9. Can function declaration be a Anonymous Function? Explain
--- yes because here function name will be ignored it take the variable for reference to call the function..
10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
"addtion" -- addtion of numbers
"square" -- to know the square of the numbers
"helloworld"  -- displays hellow world
"odd or even " -- to find the num is odd or even
```
