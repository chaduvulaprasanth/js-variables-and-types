## If Statement
1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).

  ⛑ Rule
    * [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
  ⚡️ Operations
    * [ ] Add
    * [ ] Sub
    * [ ] Mul
    * [ ] Div
    <!-- code goes here -->
    var firstnumber = +prompt("enter your number")
    var secondnumber = +prompt("enetr second number")
    var third = prompt("enter the operation you needed")
    switch(third) {
    case "+":
    alert(firstnumber+secondnumber);
    break;
    case"*":
    alert(firstnumber*secondnumber);
    break;
    case"-":
    if(firstnumber>secondnumber){
    alert(firstnumber-secondnumber);
    }
    else {
    alert("enter first number should be bigger than the second number");
    }
    break;
    case"/":
    if(firstnumber>secondnumber){
    alert(firstnumber/secondnumber);
    }
    else {
    alert("enter first number should be bigger than the second number");
    }
    break;
        default:
        alert('error')
    }

2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`
```js
var firstName = 'John';
var status = 'single';
// Your code goes here
if (status=="single") {
console.log("john is single");
}
else {
console.log("john is married");
}
```

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.
```js
// your code goes here
var num1 = prompt ("enter first number")
var num2 = prompt("enter second number")
var num3 = Number(num1);
var num4 = Number(num2);
if (num3>num4) {
alert(num3+"is bigger than"+ num4);
}
else if (num3<num4) {
alert(num3+"is lesser than"+num4);
}
else { 
alert("both are equal");
}
```

4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.

```js
// Your code goes here
var num1 = prompt ("enter first number")
var num2 = prompt("enter second number")
var num3 = prompt ("enetr third number")
var num4 = Number(num1);
var num5 = Number(num2);
var num6 = Number(num3);
var product = num4*num5*num6;
if (product>0) {
alert(`+ ${product}`);
}
else { 
alert(product);
}
```

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.
* [ ] ONE, if `number` is equal to 1.
* [ ] TWO, if `number` is equal to 2.
* [ ] THREE, if `number` is equal to 3.
* [ ] FOUR, if `number` is equal to 4.
* [ ] FIVE, if `number` is equal to 5.
* [ ] SIX, if `number` is equal to 6.
* [ ] SEVEN, if `number` is equal to 7.
* [ ] EIGHT, if `number` is equal to 8.
* [ ] NINE, if `number` is equal to 9.
* [ ] PLEASE TRY AGAIN, if  is none of the above.
```js
// Your code goes here
var a = +prompt("enter your number")
switch(a) {
case 1:
alert("ONE");
break;
case 2:
alert("TWO");
break; 
case 3:
alert("THREE");
break;
case 4:
alert("FOUR");
break;
case 5:
alert("FIVE");
break;
case 6:
alert("SIX");
break;
case 7:
alert("SEVEN");
break;
case 8:
alert("EIGHT");
break;
case 9:
alert("NINE");
break;
default:
alert("PLEASE TRY AGAIN")
}
```

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.
* [ ] `AA` if `marks` is greater than 90.
* [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
* [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
* [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
* [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
* [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
* [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
* [ ] `FF` if `marks` is less than or equal to 30
```js
// Your code goes here
var usermarks = +prompt("enter marks inbetween 0-100")
switch(true) {
    case (usermarks>90):
    alert("Your Grade is AA");
break;
case (usermarks<=90 && usermarks>80):
    alert("Your Grade is AB");
break;
case (usermarks<=80 && usermarks>70):
    alert("Your Grade is BB");
break;
case (usermarks<=70 && usermarks>60):
    alert("Your Grade is BC");
break;
case (usermarks<=60 && usermarks>50):
    alert("Your Grade is CC");
break;
case (usermarks<=50 && usermarks>40):
    alert("Your Grade is CD");
break;
case (usermarks<=40 && usermarks>30):
    alert("Your Grade is cc");
break;
case (usermarks<=30):
    alert("Your Grade is FF");
break;
default:
alert("error");
}
```
