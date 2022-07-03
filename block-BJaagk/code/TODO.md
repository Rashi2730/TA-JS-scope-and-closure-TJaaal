1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here// 

let percentage = function(marks,total) {
  return (marks * 100) / total;
}

2. Write Function Declaration or Function Expression next to the function.


function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer - declaration 



let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
// expression 

let percentage = function (marks, total) {
  return (marks * 100) / total;
};
``` 
 // expression 

```js
let percentage = (marks, total) => {
  return (marks * 100) / total; // expression 
};
```

```js
let percentage = (marks, total) => (marks * 100) / total; // expression 
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

4. Why is a function call an expression in JavaScript? 


// A function call is an expression because it consists of  the function name followed by the function call operator, () which makes it an expression. 

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
} 

let five = add(2, 3); // Answer valid 5
five = add; // Answer valid
five = five(10, 11); // Answer valid 21
five = function () {
  return 'Hello';
}; // Answer valid
```

6. What is the difference between function definition and function call? Explain with an example.

 answer -  Defining a function is the creation of a function. 

function multiple(x,y){

return x*y;

}

Calling a function is to pass values  when you actually want to invoke the function. 

let result =  multiply(2,3);

7. What is the similarities between function definition and function call?  // both are expressions

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid // valid
```

9. What is higher order function explain with an example.

a function that accepts function as parameters . 


10. Explain what is callback function. Why you can pass a function inside a function?


