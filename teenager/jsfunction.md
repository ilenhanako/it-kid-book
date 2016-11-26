var dochores = function(person1, person2) {
	console.log(person1 + " you are the chore master");
	console.log(person2 + " you need to assist " + person1);
};


//Write a function, and name it calculate
//When you run it, e.g. calculate (10, 12) it should return a message in the console "THE RESULT is 22"
//When you run it, e.g. calculate (5, 6) it should return a meesage in the console "THE RESULT is 11"

var calculate = function(number1, number2){
	var result;
	result = number1 + number2;
    console.log("the result is " + result);
}

//Write a function, and name it exerciseperweek
//If no. of exercise per week is less than 3, it should print
//YOU'RE POOR

//e.g. exerciseperweek(2)
//YOU'RE POOR

//If no. of exercise per week is 3 and above, but less than 7, it should print VERY GOOD

//If no. of exercise per week is more than 7, it should print YOU HAVE NOTHING ELSE TO DO, HUH?


var x = 14;
if (x < 10) {
	console.log("I am baby");
}

if (x >= 10 && x < 15) {
	console.log("I feel that I am teenager, but i still have baby soul");
}

//SOLUTION
```javascript
var exerciseperweek = function(abc){
        //var exerciseperweek = 3;
        if (abc < 3) {
                console.log("YOU'RE POOR");
        }

        if (abc >= 3 && abc < 7) {
                console.log("VERY GOOD");
        }

        if (abc > 7) {
                console.log("YOU HAVE NOTHING ELSE TO DO, HUH?");
        }
}
```
