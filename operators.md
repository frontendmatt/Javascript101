<pre>

#### modulus operator

var calc = 25 % 7;

document.write(calc);

#### multipler operator

var calc = 25 * 7;

document.write(calc);

#### ++ 

var increment = 7;

increment++;

document.write(increment); 

#### --

var decrement = 7;

decrement--;

document.write(decrement); 

#### assignment operators

var assign = 10;

assign += 50;
assign -= 50;
assign *= 50;
assign /= 50;
assign %= 50;

document.write(assign); 


####ternary operator 

<em>Concept:</em>
<b>(condition) ? ifTrue : ifFalse</b> 

<em>Example:</em> 
var userInput = Number(prompt("Please enter a number", ""));

var message = <b>userInput % 2 === 0 ? "Your number is even" : "You number is odd";</b>

alert(message);

<b>with multiple statements</b>
var userInput = Number(prompt("Please enter a number", ""));

var message = userInput % 2 === 0 ? 
        (alert("Your number is even"), 
        alert("and your number is " + userInput)) : 
        (alert("You number is odd"), 
        alert("and your number is " + userInput));


</pre>

