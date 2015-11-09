# Javascript101
http://frontendmatt.github.io/Javascript101

###Object data type
5 primitive data types : number, string, boolean, undefined and null. <br>
An object is an unordered list of primitive data types stored as name-value pairs within properties or methods(functions) <br>

####Primitive data type <br>
var name = "Fred"; <br>
var anotherName = name; <br>
name = "Max" <br>
log(anotherName) //Fred <br>
log(name) //Max <br>

####Reference data type <br>
var person = {name:"Fred"}; <br>
var anotherPerson = person; <br>
person.name = "Max"; <br>
log(anotherPerson.name) //Max <br>
log(person.name) //Max <br>

###Object literals
####Empty object initialised using the object literal notation <br>
var myTown = {}; <br>

####one property one method object literal
var batwing = { <br>
	status: "ready", <br>
	rescueBatman: function(){ <br>
		console.log("Hello world!"); <br>
	} <br>
}; <br>

if (batwing.status === "ready") {
	batwing.rescueBatman();
}

###functions
function halloween(name){ <br>
  return 'hello ' + name; <br>
} <br>
document.getElementById('demo').innerHTML = halloween('terry'); <br>

var xmas = function(named){ <br>
  document.getElementById('demo2').innerHTML = 'bonjour ' + named; <br>
}; <br>
xmas('june'); <br>

###conditional statements
####switch statement <br>
var age = 5; <br>
switch(age) { <br>
	case 6 : <br>
		document.write("You are 6"); <br>
		break; <br>
	case 4 : <br>
		document.write("You are 4"); <br>
		break; <br>
	default : <br>
		document.write("You are 3"); <br>
}

####ternary operator <br>
(condition) ? ifTrue : ifFalse <br>
var drinks = (age >= 21) ? true : false; <br>

####if else statement <br>
function sleepCheck(numHours) { <br>
    if(numHours >=8) { <br>
    return "You're getting plenty of sleep! Maybe even too much!"; <br>
} else { <br>
    return "Get some more shut eye!"; <br>
  } <br>0
}; <br>
sleepCheck(10); <br>

####rock, paper, scissors game <br>
var userChoice = prompt("Do you choose rock, paper or scissors?"); <br>
var computerChoice = Math.random(); <br>
if (computerChoice < 0.34) { <br>
computerChoice = "rock"; <br>
} else if(computerChoice <= 0.67) { <br>
computerChoice = "paper"; <br>
} else { <br>
computerChoice = "scissors"; <br>
} <br>

console.log("Computer: " + computerChoice); <br>

function compare(choice1, choice2) { <br>
if (choice1 === choice2) { <br>
console.log("The result is a tie!"); <br>
} else if (choice1 === "rock") { <br>
if (choice2 === "scissors"){ <br>
console.log("rock wins"); <br>
} else { <br>
console.log("paper wins"); <br>
} <br>
} <br>
} <br>
compare(userChoice, computerChoice); <br>

###looping
####while loop <br>
var i = 1; <br>
while(i <= 10) { <br>
  document.write(i + "<br>"); <br>
  i++; <br>
} <br>

var numCars = 4; <br>
var monthNumber = 1; <br>
var monthsToPrint = 12; <br>
while(monthNumber <= monthsToPrint){ <br>
  numCars = numCars * 4; <br>
	console.log("There will be " + numCars + " cars after " <br>
              + monthNumber + " month(s)!"); <br>
  monthNumber++; <br>
} <br>

####do while <br>
do { <br>
  var guess = prompt("what is the number?"); <br>
} while(guess!= 15) <br>
alert("You got it!!!"); <br>

####for loops <br>
//for loops only run when the condition is true <br>

for (i = 1; i <= 5; i++) { <br>
  document.write("Counting to 5"); <br>
} <br>

//with conditional
for (j = 0; j <= 20; j++) { <br>
  
  if((j % 2) === 0) { <br>
    continue; <br>
  } <br>
  if(j === 15) { <br>
    break; <br>
  } <br>
  document.write(j + "<br>"); <br>
} <br>

//using var
for (var counter = 1; counter < 11; counter++) { <br>
	console.log(counter); <br>
} <br>

//increment by 5 <br>
for (var i = 5; i < 51; i+=5) { <br>
	console.log(i); <br>
} <br>

//using .length <br>
var names = ["john", "paul", "george", "ringo", "fred"]; <br>
<br>
for(i=0; i < names.length; i++) { <br>
    console.log("I know someone called " + names[i]); <br>
} <br>


