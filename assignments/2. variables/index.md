1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
name is variable
```

2. Find the error if any
```js
  var product cost = 3.45;
  there should not be any inbetween spaces when you are declaring variable. below is the error that showed by consloe
  Uncaught SyntaxError: Unexpected identifier 
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" Right
  'Hello World" Wrong
  "Hello World' Wrong
  'Hello World' Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man; VALID
var 1girl; INVALID
var woman3; VALID
var -girl; INVALID
var blackDog; VALID
var 42; INVALID
var $42; VALID
var userName; VALID
var x, y, z; VALID
var x = 5, y = 6, z = 7; VALID
var x = 5 + 10 + 2; VALID
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var lessthanamount = 2000;

// Define a new variable and store the value that is 200 more then the value of amount.
var morethanamount = 2280;


// Define a new variable and store the value that is 4 times the value of amount.
var fourtimeamount = 8320

// Define a new variable and store the reminder when the value of amount is  divided by 21.
var amountnew = 2080%21;

```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark

if (johnAge>markAge) {
	alert("john is older");
}
else {
	alert("makr is older");
}
// Check who is younger
if (johnAge>markAge) {
	alert ("mark is younger");
}
	else {
	alert ("john is younger")


}
// Check if their age is equal

if (johnAge==markAge) {
	alert("their ages are equal");
}

// Create a new variable and assign the age of john to new variable.

var newjohn = johnAge;

// Check if john is equal to or greater then mark.

if (johnAge==markAge) {
	alert ("age is equal");
}
else if (johnAge>markage) {
	alert ("john age is greater than mark");
}
else {
	alert ("mark age is greater than john");
}

// Check if john is less then or equal to mark.

if (johnAge==markAge) {
	alert ("john age is equal to mark");
}
else if (johnAge>markage) {
	alert ("john age is greater than mark");
}
else {
	alert ("john age is lesser than mark");
}

// Calculate the average age of john and mark and assign to a new variable.

var averageage = (johnAge+markAge)/2;
```