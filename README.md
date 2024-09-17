 <h1>js</h1><br>

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
