
// array
var ilen = 'hello';
var age = 78;
var student = {name: "ilen", age: 78};
var todolist = ["study", "sleep", "read book"]

// loop
var i;
for(i =0; i < 5; i= i + 1) {
	console.log("hello " + i)
}

for(i =3; i <= 9; i= i + 1) {
	console.log("hello " + i)
}

for(i =3; i <= 9; i= i + 2) {
	console.log("hello " + i)
}

for(i =15; i <= 9; i= i + 2) {
	console.log("hello " + i)
}

for(i =15; i <= 9; i= i - 1) {
	console.log("hello " + i)
}

for(i =15; i > 12; i= i - 1) {
	console.log("hello " + i)
}

for (i=0; i < todolist.length ; i = i + 1) {
	console.log("I am going to " + todolist[i])
}

//task
/*
	Create a function, name it "todo". This function will accept 1 input argument (type = array).

Acceptance Criteria
Run: todo(['ab', 'cd'])
Result:
		this is ab
		this is cd

Run: todo([1, 2, "ilen"])
Result:
		this is 1
		this is 2
		this is ilen
*/

## Solution

var todo = function(number1, number2){
    var result;
    result = number1 + number2;
    console.log("this is " + result);
}

for (i=0; i < todo.length ;
