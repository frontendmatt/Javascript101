####rock, paper, scissors game <br>
var userChoice = prompt("Do you choose rock, paper or scissors?"); <br>
var computerChoice = Math.random(); <br>
if (computerChoice < 0.34) { <br>
computerChoice = "rock"; <br>
} else if(computerChoice <= 0.67) { <br>
computerChoice = "paper"; <br>
} else { <br>
computerChoice = "scissors"; <br>
} <br>

console.log("Computer: " + computerChoice); <br>

function compare(choice1, choice2) { <br>
if (choice1 === choice2) { <br>
console.log("The result is a tie!"); <br>
} else if (choice1 === "rock") { <br>
if (choice2 === "scissors"){ <br>
console.log("rock wins"); <br>
} else { <br>
console.log("paper wins"); <br>
} <br>
} <br>
} <br>
compare(userChoice, computerChoice); <br>

