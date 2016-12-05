### JSON

_FOR EXAMPLE_: 
```javascript
var student = { first_name: “Samselin”}
```
first_name: key
student: variable
Samselin: value

_TO PRINT_:
```javascript
console.log("My name is " + student.first_name )
```
_TO PRINT_: 
```javascript
console.log("My name is " + student.first_name + " " + student.last_name);
```

## Task 1
Relate to previous lesson to complete task.
Write a function, name it `whoareyou`, as such 

* when you run the function `whoareyou({first_name: "Iwan", last_name: "Soehendro"})`, it should print out `Hello there. My name is Iwan the Soehendro`
* when you run the function `whoareyou({first_name: "Masako", last_name: "Y"})`, it should print out `Hello there. My name is Masako the Y`


## Solution

```javascript
var whoareyou = function (a){
        console.log("Hello there, my name is " + a.first_name + " " + a.last_name);
}
```

## Task2
Write a function, name it `whoareyou`, as such 

* when you run the function `whoareyou({first_name: "Iwan", last_name: "Soehendro", age: 5})`, it should print out `Hello there. My name is Iwan the Soehendro. I am kid`
* when you run the function `whoareyou({first_name: "Masako", last_name: "Y", age: 20})`, it should print out `Hello there. My name is Masako the Y. I am adult`
* kid is 15 years or below, otherwise adult.

## Solution
```javascript
var whoareyou = function (a){
        if (a.age <= 15){
                console.log("Hello there, my name is " + a.first_name + " " + a.last_name + " " + "I am kid.");
        }
        if (a.age >= 16){
                console.log("Hello there, my name is " + a.first_name + " " + a.last_name + " " + "I am adult.");
        }
}
```
