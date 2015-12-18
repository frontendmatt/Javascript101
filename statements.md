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


<em>concept:</em>

if(0<1){
  document.write("this is true");
} else {
  document.write("this is false");
}


<em>example:</em>

function sleepCheck(numHours) { 
    if(numHours >= 8) { 
    return "You sleep well"; 
} else { 
    return "Are you tired?"; 
  } 
}
document.write(sleepCheck(7)); 


<em>example 2:</em>

var foo = 10;
var bar = 20;

if(foo === bar){
  document.write("the variables are equal");
} else {
  document.write("the variables are NOT equal");
}


<em>nesting if statements</em>

var foo = 5;
var bar = 6;
var baz = 7;
var qux = 4;

if(foo !== bar){
  if(qux > baz){
    document.write("the condition is true"); 
  } else {
    document.write("the condition is false");
  }
} else {
  document.write("foo and bar are NOT equal"); 
}


<em>alternative to nesting</em>

var foo = 5;
var bar = 6;

if( (foo===5) && (bar===6) ){
  document.write("all things are equal");
} else {
  document.write("all things are NOT equal");
}


<em>complex condition either or</em>

var baz = 5;
var qux = 6;

if( (baz===8) || (qux===7) ){
  document.write("the result is true");
} else {
  document.write("the result is false");
}



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

