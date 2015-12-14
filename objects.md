###Object literals
####Empty object initialised using the object literal notation <br>
var myTown = {}; <br>

####one property one method object literal
var batwing = { <br>
	status: "ready", <br>
	rescueBatman: function(){ <br>
		console.log("Hello world!"); <br>
	} <br>
}; <br>

if (batwing.status === "ready") {
	batwing.rescueBatman();
}

