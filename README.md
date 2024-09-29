<h1>js</h1><br>

<h2>languages </h2>
languages are used to write applications<br>
developers write high level code in languages<br>
and it is compiled to 0 and 1<br>

<h2>interpreted vs compiled</h2>

<h3>compilers</h3>
converts languages to o and 1<br>
write compile run<br>
dont compile if error in code<br>
strictly types<br>

<h3>interpreted</h3>
line by line<br>
run partially<br>
dynamically typed or loosely<br> typed
type script<br>
makes js static<br>

<h2>javascript</h2>
single threaded language- one core at a time<br>
variables- value can change<br>
const- constant, cant change<br>
let- local<br>
var- global<br>
datatypes- strings, numbers<br>
conditions- if, else<br>
loops- for loop<br>

<h2>complex premitive</h2>

<h3>array</h3><br> array is an ordered<br> collection of values, which can be of any data type<br>

<h3>objects </h3> <br>an object is a collection of key-value pairs<br> that allows you to store and organize data<br>

<h2>functions</h2>
take arguments, does something and return an output<br>
functions can take another function as input(callback)<br>
 

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
