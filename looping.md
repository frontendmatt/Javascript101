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

//with conditional <br>
for (j = 0; j <= 20; j++) { <br>
  
  if((j % 2) === 0) { <br>
    continue; <br>
  } <br>
  if(j === 15) { <br>
    break; <br>
  } <br>
  document.write(j + "<br>"); <br>
} <br>

//using var name <br>
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
