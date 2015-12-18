####looping

<pre>

–––––––––––––––––––––––
>> while loop << 
–––––––––––––––––––––––


var i = 1; 

while(i <= 10) { 

  document.write(i + "<br>"); 

  i++; 

} 


var numCars = 4; 

var monthNumber = 1; 

var monthsToPrint = 12; 

while(monthNumber <= monthsToPrint){ 

  numCars = numCars * 4; 

   console.log("There will be " + numCars + " cars after " 

   + monthNumber + " month(s)!"); 

  monthNumber++; 

} 

–––––––––––––––––––––––
>> do while << 
–––––––––––––––––––––––


do { 

  var guess = prompt("what is the number?"); 

} while(guess!= 15) 

alert("You got it!!!"); 



–––––––––––––––––––––––
>> for loop << 
–––––––––––––––––––––––
//for loops only run when the condition is true 


<em>concept</em>

for (i = 1; i <= 5; i++) { 

  document.write("Counting to 5"); 

} 


<em>example (with conditional):</em>

for (j = 0; j <= 20; j++) { 
  
  if((j % 2) === 0) { 

   continue; 

  } 

  if(j === 15) { 

   break; 
  
  } 
  
  document.write(j + "<br>"); 
  
} 


<em>example 2 (using var name):</em>

for (var counter = 1; counter < 11; counter++) { 

	console.log(counter); 
	
} 

<em>example 3 (increment by 5):</em>

for (var i = 5; i < 51; i+=5) { 

	console.log(i); 
	
} 


<em>example 4 (using .length)</em>

var names = ["john", "paul", "george", "ringo", "fred"]; 

for(i=0; i < names.length; i++) {

   console.log("I know someone called " + names[i]); 
    
} 

</pre>
