# 📘 JavaScript

---

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

