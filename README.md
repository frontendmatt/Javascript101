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






















#misc to sort...


function swap() {
  var myValue = document.getElementById('myTextBox').value;

  if (myValue.length === 0) {
    alert("You didn't add any text douchebag!");
    return;
  }
  var myTitle = document.getElementById('myTitle');
  myTitle.innerHTML = myValue;
}

// var userChoice = prompt("Do you choose rock, paper or scissors?");
// var computerChoice = Math.random();
// if (computerChoice < 0.34) {
// computerChoice = "rock";
// } else if(computerChoice <= 0.67) {
// computerChoice = "paper";
// } else {
// computerChoice = "scissors";
// }
//
// console.log("Computer: " + computerChoice);
//
// function compare(choice1, choice2) {
// if (choice1 === choice2) {
// console.log("The result is a tie!");
// } else if (choice1 === "rock" && choice2 === "scissors") {
// console.log("rock wins");
// } else if (choice1 === "paper" && choice2 === "scissors") {
// console.log("scissors wins");
// }
// }
// compare(userChoice, computerChoice);



var userChoice = prompt("Do you choose rock, paper or scissors?");
var computerChoice = Math.random();
if (computerChoice < 0.34) {
computerChoice = "rock";
} else if(computerChoice <= 0.67) {
computerChoice = "paper";
} else {
computerChoice = "scissors";
}

var compare = function(choice1, choice2)
{
if(choice1 === choice2)
return "The result is a tie!";

if(choice1 === "rock" && choice2 === "paper")
    return "Paper wins!";

else if(choice1 === "scissors" && choice2 === "paper")
    return "scissors wins";

if(choice1 === "paper" && choice2 === "scissors")

    return "scissors wins!";

else if(choice1 === "rock" && choice2 === "scissors")
    return "Paper wins!";

if(choice1 === "scissors" && choice2 === "rock")
    return "rock wins";

else if(choice1 === "paper" && choice2 === "rock")

    return "paper wins!";
};

var newCompare = compare(userChoice, computerChoice);
console.log(newCompare);







// var balls = document.getElementsByClassName('swap')[0];
//
// balls.addEventListener('click', hit);
//
//   function hit() {
//     document.getElementsByClassName('swap')[0].innerHTML ='Hello World!';
// }



//custom object
// function person(name, age) {
//   this.name = name;
//   this.age = age;
// }
//
// var fred = new person("Freddy", 25);
//
// console.log(fred.age);



// prototypal inheritance
// var person = {
//   first: 'default',
//   last: 'default',
//   greet: function() {
//     return 'Hi' + this.first;
//   }
// };
//
// var john = Object.create(person);
// john.first = 'John';
// john.last = 'Smith';
// console.log(john);



// //for loop
// for (var i = 0; i < 3; i++) {
//   document.write('this is a for loop <br/>');
// }
//
// // while loop
// var reg = 1;
//
// while (reg <= 2) {
//   console.log(reg + ' this is a while loop <br /');
//   reg++;
// }
//
// // do while loop
// var x = 1;
//
//   do {
//     document.write(x + ' this is a do while loop <br />');
//     x++;
//   } while(x<=2);
//
//
// // multiple parameters
// function apples(one, two) {
//   document.write('hello ' + one + ' you are ' + two + '<br/>');
// }
// apples('bob', 'cool');
//
// // return function
// function tooeasy() {
//   return "hello world! <br/>";
// }
// document.write(tooeasy());
//
// // function executing other functions
// function first(name) {
//   document.write(name + ' i am first <br/>');
// }
// function second(secondName) {
//   document.write(secondName + ' i am second <br/>');
// }
// function third() {
//   first('bob');
//   second('jeff');
// }
// third();
//
// var chop = 9;
// chop++;
// console.log(chop);
//
// var flint = 10;
// flint += 15;
// flint *= 2;
// flint -= 10;
// flint /= 1.5;
// console.log(flint);
//
// // if else
// var jon = 25;
// var paul = 26;
// // is not
// if (jon != paul) {
//   console.log('true');
// } else {
//   console.log('false');
// }
//
// var she = "tatti";
// var is = "cray";
//
// // and
// if ( (she == 'tatti') && (is == 'cray') ) {
//   console.log('true story');
// }
// // or
// if ( (she == 'tatti') || (is == 'crazy') ) {
//   console.log('or this is true');
// }
//
// // switch statement
// var harpi = "tatti";
//
// switch(harpi){
//   case "mary":
//     console.log('your name is mary');
//     break;
//   case "ashley":
//     console.log('your name is ashley');
//     break;
//   case "britney":
//     console.log('your name is britney');
//     break;
//   default:
//     console.log('this is the default');
// }
//

