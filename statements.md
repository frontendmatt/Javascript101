###return statement

function salty(){  

  return "you so salty!";
}

document.write(salty());


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