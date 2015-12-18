<pre>
–––––––––––––––––––––––
>> return statement << 
–––––––––––––––––––––––

function salty(){  

  return "you so salty!";
}

document.write(salty());

**********************
conditional statements
–––––––––––––––––––––––
>> if statement <<
–––––––––––––––––––––––

var ten = 10;
var twenty = 20;

if( ten <= twenty){
  document.write("the condition is true");
}

see also >= !== === < >

–––––––––––––––––––––––
>> if else statement <<
–––––––––––––––––––––––

<em>Concept</em>
if(0<1){
  document.write("this is true");
} else {
  document.write("this is false");
}

<em>example</em>
function sleepCheck(numHours) { 
    if(numHours >=8) { 
    return "You sleep well"; 
} else { 
    return "Are you tired?"; 
  } 
}
document.write(sleepCheck(7)); 


––––––––––––––––––––––
>> switch statement << 
––––––––––––––––––––––
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

</pre>

