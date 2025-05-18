# 📘 JavaScript
---

# 📘 Beginner-Level Programming Questions & Answers (JavaScript)

## 🧮 1. What is a variable?

**Answer:**
A variable is used to store data values.

```js
let name = "Alice"; // string
let age = 25;       // number
```

---

## 🧪 2. What are the basic data types in JavaScript?

**Answer:**

* `String` – text (e.g., `"hello"`)
* `Number` – numeric values (e.g., `42`)
* `Boolean` – true or false
* `Null` – empty or non-existent value
* `Undefined` – variable declared but not assigned
* `Object` – key-value pairs
* `Array` – list of values
* `Symbol` – unique value (advanced)

---

## ⚙️ 3. What are operators?

**Answer:**
Operators perform operations on variables and values.

```js
// Arithmetic
let sum = 5 + 3;

// Comparison
console.log(10 > 5); // true

// Logical
console.log(true && false); // false

// Assignment
let a = 10;
```

---

## 📜 4. What is the difference between `let`, `const`, and `var`?

```js
let name = "John";     // can be reassigned
const pi = 3.14;       // cannot be reassigned
var age = 20;          // function-scoped (older syntax)
```

---

## 🔁 5. What is a loop?

**Answer:**
A loop is used to repeat a block of code.

```js
// For loop
for (let i = 1; i <= 5; i++) {
  console.log(i);
}

// While loop
let i = 1;
while (i <= 5) {
  console.log(i);
  i++;
}
```

---

## 🧠 6. What is a function?

**Answer:**
A function is a reusable block of code.

```js
function greet(name) {
  console.log("Hello, " + name);
}

greet("Alice"); // Hello, Alice
```

---

## 🤔 7. What is an `if` statement?

**Answer:**
It allows conditional execution of code.

```js
let age = 18;
if (age >= 18) {
  console.log("Adult");
} else {
  console.log("Minor");
}
```

---

## 🧱 8. What is an array?

**Answer:**
An array holds multiple values in a single variable.

```js
let fruits = ["apple", "banana", "orange"];
console.log(fruits[0]); // apple
```

---

## 🧰 9. What is an object?

**Answer:**
An object stores data in key-value pairs.

```js
let person = {
  name: "John",
  age: 25
};

console.log(person.name); // John
```

---

## 🔄 10. How do you use a `switch` statement?

```js
let color = "red";

switch (color) {
  case "red":
    console.log("Stop");
    break;
  case "green":
    console.log("Go");
    break;
  default:
    console.log("Wait");
}
```

---

## 📤 11. What is the use of `return` in a function?

```js
function add(a, b) {
  return a + b;
}

let result = add(5, 3); // result = 8
```

---

## 🎯 12. What are comparison operators?

| Operator | Description  | Example    |
| -------- | ------------ | ---------- |
| `==`     | Equal to     | `5 == '5'` |
| `===`    | Strict equal | `5 === 5`  |
| `!=`     | Not equal    | `5 != 4`   |
| `>`      | Greater than | `6 > 3`    |
| `<`      | Less than    | `2 < 5`    |

---

## 🧠 13. What is the difference between `==` and `===`?

```js
5 == "5"   // true (compares value)
5 === "5"  // false (compares value + type)
```

---

## ⛔ 14. What is `null` vs `undefined`?

```js
let a = null;       // empty value
let b;              // undefined (not assigned)

console.log(a); // null
console.log(b); // undefined
```

---

## 💬 15. How do you take user input in JavaScript?

```js
let name = prompt("Enter your name:");
alert("Hello " + name);
```

> ⚠️ Works only in browsers.

---

## 💡 16. What is type coercion?

**Answer:**
Automatic or implicit conversion of values to a different type.

```js
"5" + 1   // "51" (string)
"5" - 1   // 4 (number)
```

---

## 📏 17. How do you find the length of a string or array?

```js
let str = "hello";
console.log(str.length); // 5

let arr = [1, 2, 3];
console.log(arr.length); // 3
```

---

## 🧪 18. How do you convert a string to a number?

```js
let str = "123";
let num = Number(str); // or parseInt(str)
```

---

## 🔄 19. What is a ternary operator?

**Answer:**
A shorthand for `if...else`.

```js
let age = 20;
let result = (age >= 18) ? "Adult" : "Minor";
```

---

## 🔤 20. How do you convert a number to a string?

```js
let num = 123;
let str = num.toString();
```

# 📘 JavaScript Basics – Questions and Answers
---

## 📌 Table of Contents

1. [What is JavaScript?](#1-what-is-javascript)
2. [How to add JavaScript to an HTML file?](#2-how-to-add-javascript-to-an-html-file)
3. [What are variables in JavaScript?](#3-what-are-variables-in-javascript)
4. [What is the difference between `let`, `var`, and `const`?](#4-what-is-the-difference-between-let-var-and-const)
5. [What are data types in JavaScript?](#5-what-are-data-types-in-javascript)
6. [What are operators in JavaScript?](#6-what-are-operators-in-javascript)
7. [What are functions in JavaScript?](#7-what-are-functions-in-javascript)
8. [What are arrow functions?](#8-what-are-arrow-functions)
9. [What are objects in JavaScript?](#9-what-are-objects-in-javascript)
10. [What are arrays in JavaScript?](#10-what-are-arrays-in-javascript)
11. [What is the difference between `==` and `===`?](#11-what-is-the-difference-between--and-)
12. [What is a callback function?](#12-what-is-a-callback-function)
13. [What is JSON?](#13-what-is-json)
14. [What is the DOM?](#14-what-is-the-dom)
15. [What are events in JavaScript?](#15-what-are-events-in-javascript)
16. [What is event bubbling?](#16-what-is-event-bubbling)
17. [What is `this` in JavaScript?](#17-what-is-this-in-javascript)
18. [What is scope in JavaScript?](#18-what-is-scope-in-javascript)
19. [What is hoisting?](#19-what-is-hoisting)
20. [What is a closure?](#20-what-is-a-closure)

---

## 1. What is JavaScript?

JavaScript is a **lightweight**, **interpreted** programming language primarily used to make web pages interactive.

---

## 2. How to add JavaScript to an HTML file?

```html
<script>
  alert("Hello, world!");
</script>
```

Or link external JS:

```html
<script src="script.js"></script>
```

---

## 3. What are variables in JavaScript?

Variables store data values.

```js
let name = "Alice";
```

---

## 4. What is the difference between `let`, `var`, and `const`?

* `var`: function-scoped, can be redeclared.
* `let`: block-scoped, cannot be redeclared.
* `const`: block-scoped, cannot be reassigned or redeclared.

---

## 5. What are data types in JavaScript?

* String
* Number
* Boolean
* Object
* Array
* Null
* Undefined
* Symbol (ES6)
* BigInt (ES11)

---

## 6. What are operators in JavaScript?

* Arithmetic: `+`, `-`, `*`, `/`, `%`
* Comparison: `==`, `===`, `!=`, `>`, `<`
* Logical: `&&`, `||`, `!`
* Assignment: `=`, `+=`, `-=`

---

## 7. What are functions in JavaScript?

Functions are blocks of code designed to perform a task.

```js
function greet(name) {
  return "Hello " + name;
}
```

---

## 8. What are arrow functions?

A shorter syntax for function expressions.

```js
const greet = (name) => "Hello " + name;
```

---

## 9. What are objects in JavaScript?

Objects store key-value pairs.

```js
const person = {
  name: "Alice",
  age: 25
};
```

---

## 10. What are arrays in JavaScript?

Arrays hold multiple values.

```js
let colors = ["red", "green", "blue"];
```

---

## 11. What is the difference between `==` and `===`?

* `==`: checks value only (loose equality)
* `===`: checks value and type (strict equality)

```js
'5' == 5  // true
'5' === 5 // false
```

---

## 12. What is a callback function?

A function passed as an argument to another function.

```js
function greet(callback) {
  callback();
}

greet(() => console.log("Hello!"));
```

---

## 13. What is JSON?

**JavaScript Object Notation** is a format for storing and exchanging data.

```json
{
  "name": "Alice",
  "age": 25
}
```

---

## 14. What is the DOM?

**Document Object Model** – a programming interface for HTML/XML documents.

---

## 15. What are events in JavaScript?

Events are actions like clicks, keypresses, etc.

```js
document.getElementById("btn").addEventListener("click", () => {
  alert("Clicked!");
});
```

---

## 16. What is event bubbling?

Event bubbling means the event propagates from the innermost element outward.

---

## 17. What is `this` in JavaScript?

`this` refers to the object it belongs to.

```js
const person = {
  name: "Alice",
  greet() {
    console.log(this.name);
  }
};
```

---

## 18. What is scope in JavaScript?

Scope defines where variables can be accessed:

* Global Scope
* Function Scope
* Block Scope (with `let` and `const`)

---

## 19. What is hoisting?

Hoisting moves variable/function declarations to the top of their scope before execution.

```js
console.log(x); // undefined
var x = 5;
```

---

## 20. What is a closure?

A closure is a function that remembers variables from its outer scope even after the outer function has finished executing.

```js
function outer() {
  let count = 0;
  return function () {
    count++;
    console.log(count);
  };
}

const counter = outer();
counter(); // 1
counter(); // 2
```
---

# 💼 JavaScript Interview Questions & Answers

## 📑 Table of Contents

1. [What are the different data types in JavaScript?](#1-what-are-the-different-data-types-in-javascript)
2. [What is the difference between `undefined` and `null`?](#2-what-is-the-difference-between-undefined-and-null)
3. [What is the difference between `==` and `===`?](#3-what-is-the-difference-between--and-)
4. [What is hoisting in JavaScript?](#4-what-is-hoisting-in-javascript)
5. [What is a closure?](#5-what-is-a-closure)
6. [What is the difference between `var`, `let`, and `const`?](#6-what-is-the-difference-between-var-let-and-const)
7. [What is the event loop in JavaScript?](#7-what-is-the-event-loop-in-javascript)
8. [What is a Promise in JavaScript?](#8-what-is-a-promise-in-javascript)
9. [What is the difference between synchronous and asynchronous code?](#9-what-is-the-difference-between-synchronous-and-asynchronous-code)
10. [What is `this` keyword in JavaScript?](#10-what-is-this-keyword-in-javascript)
11. [What is the difference between function declaration and function expression?](#11-what-is-the-difference-between-function-declaration-and-function-expression)
12. [What is the spread operator (`...`)?](#12-what-is-the-spread-operator-)
13. [What is destructuring in JavaScript?](#13-what-is-destructuring-in-javascript)
14. [What are arrow functions?](#14-what-are-arrow-functions)
15. [What is the difference between `map()`, `filter()` and `forEach()`?](#15-what-is-the-difference-between-map-filter-and-foreach)
16. [What is the difference between `call()`, `apply()`, and `bind()`?](#16-what-is-the-difference-between-call-apply-and-bind)
17. [What are higher-order functions?](#17-what-are-higher-order-functions)
18. [What is the use of `async` and `await`?](#18-what-is-the-use-of-async-and-await)
19. [What is the difference between deep copy and shallow copy?](#19-what-is-the-difference-between-deep-copy-and-shallow-copy)
20. [What is the Temporal Dead Zone (TDZ)?](#20-what-is-the-temporal-dead-zone-tdz)

---

## 1. What are the different data types in JavaScript?

* Primitive: String, Number, Boolean, Null, Undefined, Symbol, BigInt
* Non-Primitive: Object, Array, Function

---

## 2. What is the difference between `undefined` and `null`?

* `undefined`: A variable that has been declared but not assigned a value.
* `null`: An intentional absence of any object value.

---

## 3. What is the difference between `==` and `===`?

* `==`: Loose equality (compares values, allows type conversion)
* `===`: Strict equality (compares both value and type)

---

## 4. What is hoisting in JavaScript?

Hoisting is JavaScript's default behavior of moving declarations to the top of the current scope.

```js
console.log(a); // undefined
var a = 5;
```

---

## 5. What is a closure?

A closure is a function that has access to its own scope, the outer function’s scope, and the global scope.

```js
function outer() {
  let count = 0;
  return function inner() {
    count++;
    return count;
  };
}
```

---

## 6. What is the difference between `var`, `let`, and `const`?

* `var`: function-scoped, hoisted, can be redeclared
* `let`: block-scoped, cannot be redeclared
* `const`: block-scoped, constant value

---

## 7. What is the event loop in JavaScript?

The event loop is a mechanism that handles asynchronous callbacks in JavaScript. It moves tasks from the event queue to the call stack when the stack is empty.

---

## 8. What is a Promise in JavaScript?

A Promise represents the eventual completion (or failure) of an asynchronous operation.

```js
let promise = new Promise((resolve, reject) => {
  resolve("Success");
});
```

---

## 9. What is the difference between synchronous and asynchronous code?

* Synchronous: Executes line by line.
* Asynchronous: Executes independently of the main thread (e.g., `setTimeout`, Promises).

---

## 10. What is `this` keyword in JavaScript?

`this` refers to the object it belongs to. Its value depends on the context in which it's used.

---

## 11. What is the difference between function declaration and function expression?

```js
// Declaration
function greet() {}

// Expression
const greet = function() {};
```

Function declarations are hoisted, expressions are not.

---

## 12. What is the spread operator (`...`)?

It expands an array or object into individual elements.

```js
let arr = [1, 2];
let newArr = [...arr, 3]; // [1, 2, 3]
```

---

## 13. What is destructuring in JavaScript?

Extracting values from arrays or properties from objects into variables.

```js
let [a, b] = [1, 2];
let {name, age} = {name: "Alice", age: 25};
```

---

## 14. What are arrow functions?

A shorthand syntax for function expressions.

```js
const sum = (a, b) => a + b;
```

They do not bind their own `this`.

---

## 15. What is the difference between `map()`, `filter()` and `forEach()`?

* `map()`: returns a new array by transforming each element.
* `filter()`: returns a new array with elements that pass a condition.
* `forEach()`: executes a function on each element (no return).

---

## 16. What is the difference between `call()`, `apply()`, and `bind()`?

* `call()`: invokes a function with a given `this` and arguments.
* `apply()`: similar to `call()`, but takes arguments as an array.
* `bind()`: returns a new function with bound `this`.

---

## 17. What are higher-order functions?

Functions that take other functions as arguments or return functions.

```js
function greet(fn) {
  return fn();
}
```

---

## 18. What is the use of `async` and `await`?

They simplify handling of Promises and make asynchronous code look synchronous.

```js
async function fetchData() {
  let res = await fetch("url");
  let data = await res.json();
}
```

---

## 19. What is the difference between deep copy and shallow copy?

* **Shallow Copy**: Copies only references to nested objects.
* **Deep Copy**: Copies all levels of nested objects.

```js
// Deep copy using JSON
let newObj = JSON.parse(JSON.stringify(oldObj));
```

---

## 20. What is the Temporal Dead Zone (TDZ)?

The TDZ is the time between entering a block and the actual variable declaration where `let` and `const` cannot be accessed.

```js
console.log(a); // ReferenceError
let a = 5;
```

### 21. How do you reverse a string in JavaScript?

```js
function reverseString(str) {
  return str.split('').reverse().join('');
}
```

---

### 22. How do you check if a string is a palindrome?

```js
function isPalindrome(str) {
  const reversed = str.split('').reverse().join('');
  return str === reversed;
}
```

---

### 23. How do you find the largest number in an array?

```js
function findMax(arr) {
  return Math.max(...arr);
}
```

---

### 24. How do you remove duplicates from an array?

```js
function removeDuplicates(arr) {
  return [...new Set(arr)];
}
```

---

### 25. How do you flatten a nested array?

```js
function flattenArray(arr) {
  return arr.flat(Infinity);
}
// OR with recursion:
function flatten(arr) {
  return arr.reduce((acc, val) =>
    Array.isArray(val) ? acc.concat(flatten(val)) : acc.concat(val), []);
}
```

---

### 26. How do you check if two objects are equal?

```js
function isEqual(obj1, obj2) {
  return JSON.stringify(obj1) === JSON.stringify(obj2);
}
```

> ⚠️ Note: This works for simple objects, not complex or circular ones.

---

### 27. How do you implement a debounce function?

```js
function debounce(func, delay) {
  let timeout;
  return function (...args) {
    clearTimeout(timeout);
    timeout = setTimeout(() => func.apply(this, args), delay);
  };
}
```

---

### 28. How do you implement a throttle function?

```js
function throttle(func, limit) {
  let lastCall = 0;
  return function (...args) {
    const now = new Date().getTime();
    if (now - lastCall >= limit) {
      lastCall = now;
      func.apply(this, args);
    }
  };
}
```

---

### 29. How do you sort an array of numbers?

```js
let arr = [5, 2, 9, 1];
arr.sort((a, b) => a - b); // Ascending
```

---

### 30. How do you find the frequency of elements in an array?

```js
function frequency(arr) {
  return arr.reduce((acc, val) => {
    acc[val] = (acc[val] || 0) + 1;
    return acc;
  }, {});
}
```

---

### 31. How do you swap two variables in JavaScript?

```js
let a = 5, b = 10;
[a, b] = [b, a];
```

---

### 32. How do you generate a random number between two values?

```js
function getRandom(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}
```

---

### 33. How do you check if a number is prime?

```js
function isPrime(n) {
  if (n <= 1) return false;
  for (let i = 2; i <= Math.sqrt(n); i++) {
    if (n % i === 0) return false;
  }
  return true;
}
```

---

### 34. How do you find the factorial of a number using recursion?

```js
function factorial(n) {
  if (n === 0) return 1;
  return n * factorial(n - 1);
}
```

---

### 35. How do you find the nth Fibonacci number?

```js
function fibonacci(n) {
  if (n <= 1) return n;
  return fibonacci(n - 1) + fibonacci(n - 2);
}
```

> 🔁 Consider using **memoization** for optimization in interviews.

---

### 36. How do you implement a custom `map()` function?

```js
Array.prototype.customMap = function(callback) {
  let result = [];
  for (let i = 0; i < this.length; i++) {
    result.push(callback(this[i], i, this));
  }
  return result;
};
```

---

### 37. How do you implement a custom `filter()` function?

```js
Array.prototype.customFilter = function(callback) {
  let result = [];
  for (let i = 0; i < this.length; i++) {
    if (callback(this[i], i, this)) {
      result.push(this[i]);
    }
  }
  return result;
};
```

---

### 38. How do you clone an object?

```js
// Shallow copy
const clone = Object.assign({}, obj);
// OR
const clone2 = { ...obj };
```

---

### 39. How do you merge two objects?

```js
const merged = { ...obj1, ...obj2 };
```

---

### 40. How do you check if an object is empty?

```js
function isEmpty(obj) {
  return Object.keys(obj).length === 0;
}
```
---

# 📘 Basic Programming Questions and Answers (with JavaScript Examples)


## 🔢 1. Write a program to check if a number is even or odd.

```js
function isEven(num) {
  return num % 2 === 0 ? "Even" : "Odd";
}
```

---

## 🔢 2. Write a program to find the sum of digits of a number.

```js
function sumOfDigits(num) {
  return num.toString().split('').reduce((sum, digit) => sum + Number(digit), 0);
}
```

---

## 🔁 3. Write a program to print the factorial of a number.

```js
function factorial(n) {
  let fact = 1;
  for (let i = 2; i <= n; i++) {
    fact *= i;
  }
  return fact;
}
```

---

## 🔁 4. Print the Fibonacci series up to `n` terms.

```js
function fibonacci(n) {
  let a = 0, b = 1;
  for (let i = 0; i < n; i++) {
    console.log(a);
    [a, b] = [b, a + b];
  }
}
```

---

## 🔄 5. Reverse a number.

```js
function reverseNumber(num) {
  return parseInt(num.toString().split('').reverse().join(''));
}
```

---

## 🔤 6. Reverse a string.

```js
function reverseString(str) {
  return str.split('').reverse().join('');
}
```

---

## 🎯 7. Check if a number is prime.

```js
function isPrime(n) {
  if (n <= 1) return false;
  for (let i = 2; i <= Math.sqrt(n); i++) {
    if (n % i === 0) return false;
  }
  return true;
}
```

---

## 🔢 8. Find the greatest of three numbers.

```js
function findGreatest(a, b, c) {
  return Math.max(a, b, c);
}
```

---

## 🔁 9. Calculate the power of a number.

```js
function power(base, exponent) {
  return base ** exponent;
}
```

---

## 🔄 10. Count the number of digits in a number.

```js
function countDigits(num) {
  return num.toString().length;
}
```

---

## 🔢 11. Check if a number is an Armstrong number.

(Example: 153 → 1³ + 5³ + 3³ = 153)

```js
function isArmstrong(num) {
  let sum = 0;
  const digits = num.toString().split('');
  const power = digits.length;
  for (let digit of digits) {
    sum += Number(digit) ** power;
  }
  return sum === num;
}
```

---

## 🔁 12. Find the GCD (HCF) of two numbers.

```js
function gcd(a, b) {
  while (b !== 0) {
    [a, b] = [b, a % b];
  }
  return a;
}
```

---

## 🔁 13. Find the LCM of two numbers.

```js
function lcm(a, b) {
  return (a * b) / gcd(a, b);
}
```

---

## 🎯 14. Check if a string is a palindrome.

```js
function isPalindrome(str) {
  return str === str.split('').reverse().join('');
}
```

---

## 🔢 15. Find the largest element in an array.

```js
function findMax(arr) {
  return Math.max(...arr);
}
```

---

## 🔁 16. Find the second largest element in an array.

```js
function secondLargest(arr) {
  const unique = [...new Set(arr)];
  unique.sort((a, b) => b - a);
  return unique[1];
}
```

---

## 📋 17. Sort an array in ascending order.

```js
function sortAscending(arr) {
  return arr.sort((a, b) => a - b);
}
```

---

## 🔁 18. Count vowels in a string.

```js
function countVowels(str) {
  return (str.match(/[aeiou]/gi) || []).length;
}
```

---

## 🔤 19. Count the frequency of each character in a string.

```js
function charFrequency(str) {
  let freq = {};
  for (let char of str) {
    freq[char] = (freq[char] || 0) + 1;
  }
  return freq;
}
```

---

## 📦 20. Remove duplicates from an array.

```js
function removeDuplicates(arr) {
  return [...new Set(arr)];
}
```

## 🟨 Basics

### 🔹 Variables
- `var`: function-scoped (old)
- `let`: block-scoped (modern)
- `const`: block-scoped constant

```js
let x = 5;
const y = 10;
````

---

### 🔹 Data Types

* **Primitive**: string, number, boolean, null, undefined, symbol, bigint
* **Non-Primitive**: objects, arrays, functions

```js
let name = "Haniya";       // string
let age = 21;              // number
let isStudent = true;      // boolean
let empty = null;          // null
let notDefined;            // undefined
```

---

## 🧵 String Methods

```js
let str = "JavaScript";
```

* `str.length` → 10
* `str.toUpperCase()` → `"JAVASCRIPT"`
* `str.toLowerCase()` → `"javascript"`
* `str.indexOf("S")` → 4
* `str.slice(0, 4)` → `"Java"`
* `str.substring(0, 4)` → `"Java"`
* `str.replace("Java", "Type")` → `"TypeScript"`
* `str.includes("Script")` → true
* `str.split("")` → `["J", "a", "v", "a", ...]`
* `str.trim()` → removes whitespace

---

## 📚 Array Methods

```js
let arr = [1, 2, 3, 4];
```

* `arr.length` → 4
* `arr.push(5)` → `[1, 2, 3, 4, 5]`
* `arr.pop()` → `[1, 2, 3, 4]`
* `arr.shift()` → `[2, 3, 4]`
* `arr.unshift(0)` → `[0, 2, 3, 4]`
* `arr.join("-")` → `"1-2-3-4"`
* `arr.concat([5, 6])` → `[1, 2, 3, 4, 5, 6]`
* `arr.slice(1, 3)` → `[2, 3]`
* `arr.splice(1, 2)` → modifies array

---

## 🔁 Array Methods (High-order)

### 🔸 map()

* Creates a new array by applying a function to each element.

```js
const nums = [1, 2, 3];
const doubled = nums.map(n => n * 2); // [2, 4, 6]
```

---

### 🔸 filter()

* Returns a new array with elements that pass a condition.

```js
const nums = [1, 2, 3, 4, 5];
const evens = nums.filter(n => n % 2 === 0); // [2, 4]
```

---

### 🔸 reduce()

* Reduces array to a single value.

```js
const nums = [1, 2, 3, 4];
const sum = nums.reduce((acc, curr) => acc + curr, 0); // 10
```

---

### 🔸 find()

* Returns the first element that matches the condition.

```js
const nums = [5, 12, 8, 130, 44];
const found = nums.find(n => n > 10); // 12
```

---

### 🔸 some()

* Returns true if **at least one** element passes the test.

```js
[1, 2, 3].some(n => n > 2); // true
```

---

### 🔸 every()

* Returns true if **all** elements pass the test.

```js
[1, 2, 3].every(n => n > 0); // true
```

---

### 🔸 includes()

* Checks if array contains a value.

```js
[1, 2, 3].includes(2); // true
```

---

### 🔸 sort()

* Sorts the array (default is lexicographic).

```js
[1, 30, 4, 21].sort();              // [1, 21, 30, 4]
[1, 30, 4, 21].sort((a, b) => a - b); // [1, 4, 21, 30]
```

---

### 🔸 reverse()

* Reverses the array in-place.

```js
[1, 2, 3].reverse(); // [3, 2, 1]
```

---

### 🔸 flat()

* Flattens nested arrays into a single level.

```js
[1, [2, 3], [4, 5]].flat(); // [1, 2, 3, 4, 5]
```

---

### 🔸 flatMap()

* First maps each element, then flattens the result.

```js
[1, 2, 3].flatMap(n => [n, n * 2]); // [1, 2, 2, 4, 3, 6]
```

---

## 🧠 Functions

### Function Declaration

```js
function greet(name) {
  return "Hello " + name;
}
```

### Function Expression

```js
const greet = function(name) {
  return "Hi " + name;
};
```

---

## ⚡ Arrow Functions

```js
const add = (a, b) => a + b;
const greet = name => `Hello ${name}`;
```

---

## 📦 JSON (JavaScript Object Notation)

```js
const obj = { name: "Ali", age: 25 };
const jsonStr = JSON.stringify(obj); // Convert object → string
const parsed = JSON.parse(jsonStr);  // Convert string → object
```

---

## 🧮 Math Methods

* `Math.floor(4.7)` → 4
* `Math.ceil(4.3)` → 5
* `Math.round(4.5)` → 5
* `Math.max(10, 20)` → 20
* `Math.min(10, 20)` → 10
* `Math.random()` → 0 to <1

---


## 🧾 JavaScript Objects & Methods

### 🔸 Object Methods

```js
function objectMethods(obj) {
  console.log("Original Object:", obj);

  let keys = Object.keys(obj);
  console.log("After Object.keys():", keys); // [ 'key1', 'key2', 'key3' ]

  let values = Object.values(obj);
  console.log("After Object.values():", values); // [ 'value1', 'value2', 'value3' ]

  let entries = Object.entries(obj);
  console.log("After Object.entries():", entries); // [ [ 'key1', 'value1' ], ... ]

  let hasProp = obj.hasOwnProperty("property");
  console.log("After hasOwnProperty():", hasProp); // false

  let newObj = Object.assign({}, obj, { newProperty: "newValue" });
  console.log("After Object.assign():", newObj);
}

const sampleObject = {
  key1: "value1",
  key2: "value2",
  key3: "value3",
};

objectMethods(sampleObject);
````

---

## ⏱️ setTimeout Example

```js
function findSum(n) {
  let ans = 0;
  for (let i = 0; i < n; i++) {
    ans += i;
  }
  return ans;
}

function findSumTill100() {
  console.log(findSum(100));
}

setTimeout(findSumTill100, 1000);
console.log("hii");
```

---

## 📁 File Read Example (Node.js)

```js
const fs = require("fs");

fs.readFile("a.txt", "utf-8", function (err, data) {
  console.log(data);
});

console.log("hi, hello");

let a = 0;
for (let i = 0; i < 10000000; i++) {
  a++;
}

console.log("hi bye");
```

---

## ⚠️ Syntax Error Fix (findSum example)

```js
function findSum(n) {
  let ans = 0;
  for (let i = 0; i < n; i++) {
    ans += i;
  }
  return ans;
}

function findSumTill100() {
  console.log(findSum(100));
}

setTimeout(findSumTill100, 1000);
console.log("hii");
```

---

## 🔼 Arrow Functions

```js
const add = (a, b) => a + b;
```

---

## 🔄 Array Methods

### 🧭 `map()` Method

* Transforms every element in the array using a function.
* Does not mutate the original array.

```js
const nums = [1, 2, 3];
const squares = nums.map(n => n * n); // [1, 4, 9]
```

---

### 🧹 `filter()` Method

* Filters out elements based on a condition (returns `true` or `false`).
* Creates a new array with elements that pass the condition.

```js
const nums = [1, 2, 3, 4, 5];
const even = nums.filter(n => n % 2 === 0); // [2, 4]
```

