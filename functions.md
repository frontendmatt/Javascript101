###functions

<pre> 

function boston(name){ 

document.write("hello " + name);

}

boston("dave");

</pre>

##### using a return statement
<pre>

function blue(name){

return "you so greasy " + name;

}

document.write(blue("dave")); 

</pre>


###calling functions from a function

<pre>

function doFirst(){

document.write("I am first");

}

function doSecond(){

document.write("I am second");

}

function start(){

doFirst();

doSecond();

}

start();

</pre>
