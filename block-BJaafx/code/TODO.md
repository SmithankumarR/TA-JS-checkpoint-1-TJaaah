1. Using loops take 10 inputs from user and find the average of all the numbers.
let n1 = +prompt("enter the number to find average);
let n2 = +prompt("enter the number to find average);
let n3 = +prompt("enter the number to find average);
let n4 = +prompt("enter the number to find average);
let n5 = +prompt("enter the number to find average);
let n6 =  +prompt("enter the number to find average);
let n7 = +prompt("enter the number to find average);
let n8 = +prompt("enter the number to find average);
let n9 =  +prompt("enter the number to find average);
let n10 =  +prompt("enter the number to find average);
for(let i= 0; i<= number; i++ ) {
  let average = (n1 + n2+ n3+ n4+ n5+ n6+n7+ n8+ n9+ n10) / 10;
  alert(` The average of all the input is ${average}`);

}    
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  print('hi');
  i++;
}
``` 
 // print the whole page wntils the gets gets false

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
let getEvenSum = (max) =>{
  let sum = 0;
  const max = 10;
  for(let i = 0; i<= max; i++) {
    if( i % 2 == 0) {
      sum += i;
    } else {
      console.log("odd number");
    }
  }
  return sum;
}
  

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

let getproductofDigits = (num) => {
 let product = num;
 for(let i =1; i<= num; i++) {
   product *= i;
   if( num <= 0 ) {
     return `not a valid input`;
   }
 }
 return product; 
}

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // Bigger than 5 , because it checks the given condition through given function value 
check(1); //  smaller than 5 , 
check(5); // 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); //  you are Arya , 
getOutput('John'); // you are John
getOutput(); // who are you ,  here if the gives matches the given conditon with is datatype then the condition gets executed or  else returns the defsult statement
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); //  returns undifined prints you are Arya
getOutput('John'); // returns undifined prints you are John  only if the condition matches
getOutput(); //  returns who are you
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
<!-- A function can have multiple return statements but only one of them will be executed because once a return statement is executed, the program control moves back to the caller function skipping the remaining statements of the current function. -->
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
  return 'why are here` ;
  return `what is your Aim`;

}

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
 foor loop -- if user know how many times to repeat the condition then we are going to use for loop 
 while loop -- if user doesnt know how much time to repet then we have to use while or do while loop

 