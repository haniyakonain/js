<h1>js</h1><br>

languages
languages are used to write applications
developers write high level code in languages
and it is compiled to 0 and 1

interpreted vs compiled

compilers
converts languages to o and 1
write compile run
dont compile if error in code
strictly types
interpreted
line by line
run partially
dynamically typed or loosely typed
type script
makes js static

javascript
single threaded language_ one core at a time
variables- value can change
const- constant, cant change
let- local
var- global

datatypes- strings, numbers
conditions- if, else
loops- for loop

complex premitive
array- array is an ordered collection of values, which can be of any data type
objects-  an object is a collection of key-value pairs that allows you to store and organize data

functions
take arguments, does something and return an output
functions can take another function as input(callback)
 

<h2>arrow function ( => )</h2>

Arrow functions provide a concise way to write function expressions in JavaScript. <br>They have a shorter syntax and lexically bind this<br><br>
example- <br>// Regular function<br>
function add(a, b) {<br>
  return a + b;<br>
}<br>

// Arrow function<br>
const add = (a, b) => a + b;<br>

<h2>map()</h2>
it transforms array<br>
global function on array class <br><br>
1) initial array (arr) <br>
2) transformation function (f) <br>
3) map (arr, f) <br>
4)gives final output <br><br>
Creates a new array with the results of calling a provided<br> function on every element in the array.<br>
Does not change the original array.<br>


<h2>filter()</h2>
it transforms array<br>
global function on array class <br>
input can be anything number or character or string <br><br>
Creates a new array with all elements that pass the test<br> implemented by the provided function.<br>
The callback function should return true to keep the element, <br>or false to discard it.<br>
