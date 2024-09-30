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

<h3>array</h3> array is an ordered<br> collection of values, which can be of any data type<br>

<h3>objects </h3> an object is a collection of key-value pairs<br> that allows you to store and organize data<br>

<h2>functions</h2>
take arguments, does something and return an output<br>
functions can take another function as input(callback)<br>
 

<h2>arrow function ( => )</h2>

Arrow functions provide a concise way to write function expressions in JavaScript. <br>They have a shorter syntax and lexically bind this<br><br>
example- <br>// Regular function<br>
function add(a, b) {<br>
  return a + b;<br>
}<br>

//LEVEL 1
/////////////////STRINGS

//LENGTH
//gives the total length not index
/*const str="haniya";
console.log(str.length);

//index
//gives index, if word not present it gives -1
function findIndexOf(str, target) {
  console.log("Original String:", str);
  console.log("Index:", str.indexOf(target));
}
findIndexOf("Hi hello", "hello"); 

//two same stirngs, gives index of first word
function findIndexOf(str, target) {
  console.log("Original String:", str);
  console.log("Index:", str.indexOf(target));
}
findIndexOf("Hi hello hello", "hello");

//last index
function findIndexOf(str, target) {
  console.log("Original String:", str);
  console.log("Index:", str.lastIndexOf(target));
}
findIndexOf("Hi hello how are you", "are"); 

// slice, gives a part of string
function getSlice(str, start, end) {
  console.log("Original String:", str);
  console.log("After slice:", str.slice(start, end));
}
getSlice("Hello World", 0, 5);

// substring, number of string
function getSubstring(str, start, end) {
  console.log("Original String:", str);
  console.log("After substring:", str.substring(start, end));
}
getSubstring("Hello World", 0, 8);

// split, has a delimeter like ",", "hi", " " , gives it into a array
function splitString(str, separator) {
  console.log("Original String:", str);
  console.log("After split:", str.split(separator));
}
splitString("Hello World", " ");

// trim, removes extra spaces
function trimString(str) {
  console.log("Original String:", str);
  console.log("After trim:", str.trim());
}
trimString("                hi         Haniya konain              ");

// toUpperCase
function toUpper(str) {
  console.log("Original String:", str);
  console.log("After toUpperCase:", str.toUpperCase());
}
toUpper("haniya");

// toLowerCase
function toLower(str) {
  console.log("Original String:", str);
  console.log("After toLowerCase:", str.toLowerCase());
}
toLower("Hi bye");

///////////////NUMBERS
//parseInnt and parseFloat are global functions, convert string to integer by removing extras like char or float from integer, if there are charcters in front and end and integers in middle it gives NAN
console.log(parseInt("42hhh"));
console.log(parseInt("123px"));
console.log(parseInt("3.14"));
//it allows decimal also
console.log(parseFloat("3k"));
console.log(parseFloat("3.14"));

///////////////ARRAYS

//push adds elements at end of array
function pushExample(arr, element) {
  console.log("Original Array:", arr);

  arr.push(element);
  console.log("After push:", arr);
}
pushExample([1, 2, 3], 4);

// pop removes elements at end of array
function popExample(arr) {
  console.log("Original Array:", arr);

  arr.pop();
  console.log("After pop:", arr);
}
popExample([1, 2, 3]);

// shift, it pop elements from front of array
function shiftExample(arr) {
  console.log("Original Array:", arr);

  arr.shift();
  console.log("After shift:", arr);
}
shiftExample([1, 2, 3]);

// unshift it push elements from front of array
function unshiftExample(arr, element) {
  console.log("Original Array:", arr);

  arr.unshift(element);
  console.log("After unshift:", arr);
}
unshiftExample([1, 2, 3], 0);

// concat merge 2 arrays
function concatExample(arr1, arr2) {
  console.log("Original Arrays:", arr1, arr2);

  let arr3 = arr1.concat(arr2);
  console.log("After concat:", arr3);
}
concatExample([1, 2, 3], [4, 5, 6]);

// forEach, log in new line
function forEachExample(arr) {
  console.log("Original Array:", arr);

  arr.forEach(function(item, index) {
    console.log(item, index);
  });
}
forEachExample([1, 2, 3]);

//LEVEL 2
/////////////////////////CLASSES
//blueprint, group of same thing for reusibility, has attributes and functions
lass Animal {
  constructor(name, legCount) {
    this.name = name
    this.legCount = legCount
  }
  describe() {
    return `${this.name} has ${this.legCount} legs`
  }
}
// static function can be called without creating objects, not associated to objects, can be calles directly
  static speak() {
    return "Animal can speak";
  }

//////////////////DATE
//print current time and how muuch time a program runned
function dateMethods() {
  const currentDate = new Date();
  console.log("Current Date:", currentDate);

  // Getting various components of the date
  console.log("Date:", currentDate.getDate());
  console.log("Month:", currentDate.getMonth() + 1); // Months are zero-indexed, so adding 1
  console.log("Year:", currentDate.getFullYear());
  console.log("Hours:", currentDate.getHours());
  console.log("Minutes:", currentDate.getMinutes());
  console.log("Seconds:", currentDate.getSeconds());

  // Setting components of the date
  currentDate.setFullYear(2022);
  console.log("After setFullYear:", currentDate);

  currentDate.setMonth(5); // Setting month to June (zero-indexed)
  console.log("After setMonth:", currentDate);

  // Getting and setting time in milliseconds since 1970
  console.log("Time in milliseconds since 1970:", currentDate.getTime());

  const newDate = new Date(2023, 8, 15); // Creating a new date
  console.log("New Date:", newDate);
}

// Example Usage for Date Methods
dateMethods();

///////////////////JSON JAVASCRIPT OBJECT NOTATION 
//Send data somewhere, object to string and vice versa
function jsonMethods(jsonString) {
  console.log("Original JSON String:", jsonString);

  // Parsing JSON string to JavaScript object
  let parsedObject = JSON.parse(jsonString);
  console.log("After JSON.parse():", parsedObject);

  // Stringifying JavaScript object to JSON string, key should have ""
  let jsonStringified = JSON.stringify(parsedObject);
  console.log("After JSON.stringify():", jsonStringified);
}

// Example Usage for JSON Methods
const sampleJSONString =
  '{"key": "value", "number": 42, "nested": {"nestedKey": "nestedValue"}}';

jsonMethods(sampleJSONString);

////////////////////////MATH 
function mathMethods(value) {
  console.log("Original Value:", value);

  let rounded = Math.round(value);
  console.log("After round():", rounded);

  let ceiling = Math.ceil(value);
  console.log("After ceil():", ceiling);

  let flooring = Math.floor(value);
  console.log("After floor():", flooring);

  let randomValue = Math.random();
  console.log("After random():", randomValue);

  let maxValue = Math.max(5, 10, 15);
  console.log("After max():", maxValue);

  let minValue = Math.min(5, 10, 15);
  console.log("After min():", minValue);

  let powerOfTwo = Math.pow(value, 2);
  console.log("After pow():", powerOfTwo);

  let squareRoot = Math.sqrt(value);
  console.log("After sqrt():", squareRoot);
}

// Example Usage for Math Methods
mathMethods(4.56);
mathMethods(9);
mathMethods(25);

//////////////////////////OBJECTS
// Object Methods object.keys gives array, it is a string
  console.log("Original Object:", obj);

  let keys = Object.keys(obj);
  console.log("After Object.keys():", keys);

  let values = Object.values(obj);
  console.log("After Object.values():", values);
  
//entries, first index is key second is value
  let entries = Object.entries(obj);
  console.log("After Object.entries():", entries);

//has own property prints true or false
  let hasProp = obj.hasOwnProperty("property");
  console.log("After hasOwnProperty():", hasProp);

  let newObj = Object.assign({}, obj, { newProperty: "newValue" });
  console.log("After Object.assign():", newObj);

}

// Example Usage for Object Methods
const sampleObject = {
  key1: "value1",
  key2: "value2",
  key3: "value3",
};

objectMethods(sampleObject);


day4
function findSum(n) {
let ans= 0;
for (i = 0; i < n; i++) {
ans += i;
}
return ans;
}
function findSumTill100() {
console.log(findSum(100));
}
//waiting

setTimeout(findSumTill100, 1000)
console.log("hii");*/

const fs= require("fs");
fs.readFile("a.txt", "utf-8", function(err, data) {
  console.log(data);
})
console.log("hi, hello");
let a= 0;
for (let i = 0; i < 10000000; i++) {
  a++;
}
console.log("hi bye");

    function findSum(n){
let ans= 0;
fot(i=0; i<n; i++)
ans +- i;
}
return ans;
}
function findSumTill100(){
console.log(findSum(100));
}
//waiting

setTimeout  (findSumTill100, 1000)
console.log("hii");    


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
