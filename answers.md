###Convert Minutes into Seconds

```
function convert(minutes) {
	return minutes*60
}

```
###Return the Next Number from the Integer Passed

```
function addition(num) {
	return ++num
}

```
###Area of a Triangle

```
function triArea(base, height) {
	return (base*height)/2
}
```
###Convert Age to Days

```
function calcAge(age) {
	return age * 365
}
```
###Buggy Code (Part 1)

```
function cubes(a) {
	return a ** 3
}
```
###Power Calculator

```
function circuitPower(voltage, current) {
	return voltage * current
}

```
###Convert Hours into Seconds

```
function howManySeconds(hours) {
	return hours*60**2
}

```
###Maximum Edge of a Triangle

```
function nextEdge(side1, side2) {
	return (side1+side2)-1
}

```
###Return the Remainder from Two Numbers

```
function remainder(x, y) {
	return x%y
}

```
###Find the Perimeter of a Rectangle

```
function findPerimeter(length, width) {
	return (length+width)*2
}

```
###Return Something to Me!

```
function giveMeSomething(a) {
	return `something ${a}`
}

```
###Basic Variable Assignment

```
function nameString(name){
	var b = "Edabit"
	var result = name + b
  	return result
}

```
###Correct the Mistakes

```
function squared (b) {
	return b * b;
}

```
###Is the Number Less than or Equal to Zero?

```
function lessThanOrEqualToZero(num) {
	return num>0?false:true
}

```
###Sum of Polygon Angles

```
function sumPolygon(n) {
	return (n - 2) * 180
}

```
###Basketball Points

```
function points(twoPointers, threePointers) {
	return (twoPointers*2)+(threePointers*3)
}

```
###Less Than 100?

```
function lessThan100(a, b) {
	return a+b>=100?false:true 
}

```
###Buggy Code (Part 5)

```
function printArray(number) {
  var newArray = [];

  for(let i = 1; i <= number; i++) {
    newArray.push(i);
  }
  return newArray;
}
```
###Buggy Code (Part 7)

```
function swap(a, b) {
	return [b, a]
}
```
###The Farm Problem

```
function animals(chickens, cows, pigs) {
	chickens=chickens*2
	cows=cows*4
	pigs=pigs*4
	return chickens+cows+pigs
}
```

###Using the "&&" Operator

```
function and(a, b) {
	return a && b
}
```
###Are the Numbers Equal?

```
function isSameNum(num1, num2) {
	return num1 === num2?true:false
}
```
###Football Points

```
function footballPoints(wins, draws, losses) {
	wins=wins*3
	return wins+draws
}
```
###Convert Hours and Minutes into Seconds

```
function convert(hours, minutes) {
	hours=(hours*60)*60;
	let result =(minutes*60)+hours;
	return result
}

```
###Fix the Expression

```
function isSeven(x) {
	return x=="7"?true:false;
}

```
###Equality Check

```
function checkEquality(a, b) {
  return a===b
}

```
###Profitable Gamble

```
function profitableGamble(prob, prize, pay) {
	return (prob*prize)-pay>0
}

```
###Boolean to String Conversion

```
function boolToString(flag) {
	return String(flag)
}

```
###Using Arrow Functions

```
// create your arrow function below
const arrowFunc=(a)=>{
	return a
}

```
###Frames Per Second

```
function frames(minutes, fps) {
	minutes=minutes*60;
	return minutes*fps;
}

```
###Miserable Parody of a Calculator

```
function calculator(str) {
	return eval(str)
}

```

30 ta bo'ldi

###Reusable numbers !

```
const arr=[1,1,2,2,4,3,5,3,3]
let reusableNum=0;
for(let i = 0; i<arr.length; i++){
    if(arr[i]==5){
        reusableNum++
    }
}

console.log(reusableNum)

```
###Finds the sum of the numbers in arr.

```
const arr=[10,2,3];
let result=0;
for(let i = 0; i< arr.length; i++){
    result+=arr[i];
   }

console.log(result);


```
###Determining which number is the square of a number:

```
let n=10000;
const kvadrat= (1/0);

for(let i = 0; i<=kvadrat; i++){
    if(i**2==n){
        console.log(`bu son ${i} ning kvadrati hisoblanadi. `)
    }else{
        
    }
}



```
###Find the largest number in an array.

```
const arr=[110,334,-1,35,30];

for(let i=0;i <arr.length; i++){
    if(bestBig>arr[i]){
    }else{
       var bestBig=arr[i]
        console.log(bestBig)
    }
}

```
###Buggy Code (Part 4)


```
function greeting(name) {
 if(name === "Mubashir") {
    return "Hello, my Love!";
  }else{
		 return "Hello, " + name + "!";
	}
}

```
###Two Makes Ten


```
function makesTen(a, b) {
	return a+b==10 || a==10|| b==10;
}

```
###Let's Fuel Up!


```
function calculateFuel(n) {
	return n*10>=100?n*10:100
}
```

###Buggy Code (Part 2)


```
function maxNum(n1,n2) {
	return n1>=n2?n1:n2
}

```
###Pair Management


```
function makePair(num1, num2) {
	return [num1,num2]
}

```
###Compare Strings by Count of Characters


```
function comp(str1, str2) {
	return str1.length==str2.length
}

```

40ta bo'ldi .

###Is the String Empty?


```
function isEmpty(s) {
	return !s
}

```
###Check if an Integer is Divisible By Five


```
function divisibleByFive(n) {
	return !Boolean(n%5)
}

```
###Multiple of 100


```
function divisible(num) {
	return num %100==0
}

```
###Recursion: Length of a String

```
function length(str) {
	return str.length
}

```
###Divides Evenly

```
function dividesEvenly(a, b) {
	return a%b===0
}
```
###Return a String as an Integer

```
function dividesEvenly(a, b) {
	return a%b===0
}
```
###Area of a Rectangle

```
function area(h, w) {
	return h>0 && w>0&& h*w>0?h*w:-1
}

```

###How to make push method ?.

```

const comingInfo=prompt("ixtiyoriy narsa kiriting !")

let arr=["one",true,123,"hello"];
var best;
for(let i=0; arr[i]!==undefined; i++){
    var best=i+1
}
arr[best]=comingInfo;
console.log(arr);

```
















