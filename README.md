# Javascript101

###functions
`function halloween(name){
  return 'hello ' + name;
}
document.getElementById('demo').innerHTML = halloween('terry');

var xmas = function(named){
  document.getElementById('demo2').innerHTML = 'bonjour ' + named;
};
xmas('june');`

###conditional operators
`//switch statement
var age = 5;
switch(age) {
	case 6 :
		document.write("You are 6");
		break;
	case 4 :
		document.write("You are 4");
		break;
	default : 
		document.write("You are 3");
}

//ternary operator
(condition) ? ifTrue : ifFalse
var drinks = (age >= 21) ? true : false;`

###looping
`//while loop
var i = 1;
while(i <= 10) {
  document.write(i + "<br />");
  i++;
}

//do while
do {
  var guess = prompt("what is the number?");
} while(guess!= 15)
alert("You got it!!!");

//for loops
for (i = 1; i <= 5; i++) {
  document.write("Counting to 5");
}

for (j = 0; j <= 20; j++) {
  
  if((j % 2) === 0) {
    continue;
  }
  if(j === 15) {
    break;
  }
  document.write(j + "<br />");
}`

