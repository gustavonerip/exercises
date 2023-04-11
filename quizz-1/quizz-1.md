### Javascript Test

Just a quick test to test your javascript understanding.

###### 1- What is ES6?

ES6 is the standard newer version of JavaScript (ECMAScript 6).

###### 2- Name 3 examples of ES6 features.

1. Let and Const keywords
2. Promises
3. Multi-line strings

###### 3- What is the difference between let and const?

Const cannot be reassigned but Let can.

###### 4- How do you access object values? Give 3 examples

1. object.property
2. object['property']
3. const { property } = object

###### 5- What does setInterval and setTimeout do?

setInterval calls a function at specified intervals (in miliseconds) and setTimeOut calls a function after a number of milliseconds only once.

###### 6- What are promises?

Promises are objects that represents either a failure or successful completition of an asyncronous operation.

###### 7- Convert this async function to async/await

```js
getQuote().then((quote) => {
  console.log(quote);
}).catch(function(err) {
  console.log(err);
});
// after this line,
try {
  const quote = await getQuote();
  console.log(quote);
} catch (err) {
  console.log(err);
}
```
  
###### 8- Convert this code to arrow function.

```js
function greeting(firstname, lastname) {
  return `Hello ${firstname} ${lastname}`;
}
// after this line,
const greeting = (firstname, lastname) => `Hello ${firstname} ${lastname}`;
```

###### 9- Explain what a callback function is.

Callback function is a function passed as an argument to another function.

###### 10- What does the functions pop and push do to an array?

pop - removes the last element of an array and returns that element.
push - Adds elements to the end of an array and returns the new length of that array.

###### 11- What is the expected answer to this code?

```js
let string = "";
let object = { a: 1, b: 2, c: 3 };
for (let key in object) {
  string += object[key];
}
console.log(string);
```

The expected answer is "123"

###### 12- What data type would Array.map() and Array.filter() return?

They both return a new array.

###### 13- What data type would Array.includes() and Array.some() return?

They both return boolean data (true or false).

###### 14- Write down the 4 main methods of rest api

1. GET: used to retrieve or fetch data from the server.
2. POST: used to input data to the server.
3. PUT: used to update existing data in the server.
4. DELETE: used to delete data from the server.

###### 15- What is the difference between JSON and a JavaScript object?

1. JSON has a string-based syntaz while JavaScript object is a native data type.
2. JSON also requires double quotes around properties.
3. JSON used to exchange data between systems while JavaScript is an in-memory data structure.