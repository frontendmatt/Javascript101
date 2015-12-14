###Object data type
5 primitive data types : number, string, boolean, undefined and null. <br>
An object is an unordered list of primitive data types stored as name-value pairs within properties or methods(functions) <br>

####Primitive data type <br>
var name = "Fred"; <br>
var anotherName = name; <br>
name = "Max" <br>
log(anotherName) //Fred <br>
log(name) //Max <br>

####Reference data type <br>
var person = {name:"Fred"}; <br>
var anotherPerson = person; <br>
person.name = "Max"; <br>
log(anotherPerson.name) //Max <br>
log(person.name) //Max <br>
