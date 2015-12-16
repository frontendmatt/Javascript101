###variables

<pre>

var x = 42;

document.write(x);

var y = "this is a string";

document.write(y);

</pre>

###global variables
* exist outside the body of a function

<pre>

var girl = " kelsey ";

function foo(){
  
document.write(girl);

}

foo();

document.write(girl); < prints to screen because 'girl' is a global variable

</pre>

###local variable
* exist inside body of a function

<pre>

function bar(){

var boy = " freddy ";
  
document.write(boy);

}

bar();

document.write(boy); < ignored because 'boy' is a local variable 

</pre>

