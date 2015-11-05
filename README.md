# Javascript101
http://frontendmatt.github.io/Javascript101

###Object data type
5 primitive data types : number, string, boolean, undefined and null. <br />
An object is an unordered list of primitive data types stored as name-value pairs within properties or methods(functions) <br />

//Primitive data type <br />
var name = "Fred"; <br />
var anotherName = name; <br />
name = "Max" <br />
log(anotherName) //Fred <br />
log(name) //Max <br />

//Reference data type <br />
var person = {name:"Fred"}; <br />
var anotherPerson = person; <br />
person.name = "Max"; <br />
log(anotherPerson.name) //Max <br />
log(person.name) //Max <br />

###Object literals
//Empty object initialised using the object literal notation <br>
var myTown = {}; <br>

//one property one method object literal
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
function halloween(name){ <br />
  return 'hello ' + name; <br />
} <br />
document.getElementById('demo').innerHTML = halloween('terry'); <br />

var xmas = function(named){ <br />
  document.getElementById('demo2').innerHTML = 'bonjour ' + named; <br />
}; <br />
xmas('june'); <br />

###conditional operators 
//switch statement <br />
var age = 5; <br />
switch(age) { <br />
	case 6 : <br />
		document.write("You are 6"); <br />
		break; <br />
	case 4 : <br />
		document.write("You are 4"); <br />
		break; <br />
	default : <br />
		document.write("You are 3"); <br />
}

//ternary operator <br />
(condition) ? ifTrue : ifFalse <br />
var drinks = (age >= 21) ? true : false; <br />

###looping
//while loop <br />
var i = 1; <br />
while(i <= 10) { <br />
  document.write(i + "<br />"); <br />
  i++; <br />
} <br />

//do while <br />
do { <br />
  var guess = prompt("what is the number?"); <br />
} while(guess!= 15) <br />
alert("You got it!!!"); <br />

//for loops <br />
for (i = 1; i <= 5; i++) { <br />
  document.write("Counting to 5"); <br />
} <br />

for (j = 0; j <= 20; j++) { <br />
  
  if((j % 2) === 0) { <br />
    continue; <br />
  } <br />
  if(j === 15) { <br />
    break; <br />
  } <br />
  document.write(j + "<br />"); <br />
} <br />
