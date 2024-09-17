# js

arrow function ( => )

Arrow functions provide a concise way to write function expressions in JavaScript. <br>They have a shorter syntax and lexically bind this
// Regular function
function add(a, b) {
  return a + b;
}

// Arrow function
const add = (a, b) => a + b;



map();
Creates a new array with the results of calling a provided function on every element in the array.
Does not change the original array.


filter():

Creates a new array with all elements that pass the test implemented by the provided function.
The callback function should return true to keep the element, or false to discard it.
