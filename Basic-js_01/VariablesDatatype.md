VARIABLE

//The meaning of keyword const is once declared it cannot be changed
// try to change the value of accountId
const accountId=12345
 <!--you can use const keyword when you want to define a variable in a such a way that it shouldnt be changed throughout the codebase  -->

// nowadays we dont use var but two ways to change variables let and var.
let accountusname="ramya"
var accountpass="Ra@97"
<!-- we dont use var anymore due to the issue of blocka and dunctional scope -->

accountCity="Mumbai"
<!-- Javascript is such a safe language that we dont to declare a keyword at times and if we just use a varibale it itself declares its type based on the value/string assigned to the variable -->

// two ways to print on terminal 
console.log(accountId)
console.table([accountId,accountusname,accountpass])
<!-- when a variable is not defined its value is printed as undefined on the console -->

-------------------------------------------------------------------------------------------------------------------------------------------------------------

DATATYPE

"use strict;" //use new code as new js version

alert(3+3) //this is for browser not for node.js

<!-- the main thing in coding is readability -->
console.log("rae"); console.log("hi")
//this isnt the right way to write

<!-- this is the right way -->
console.log("rae")
console.log("hi")

<!-- lets understand about datatype -->

let username="ramya" //string
let password="rae@Rae" //string
let number=123456789 //number sometimes u use bigInt 
let userLogin=true //boolean either true or false
 let state = null //null is a standalone value and there is undefined where if u dont define a variable with a value then the value of variable is undefined
//symbol is used to find unquiness 

//object 

  <!-- conversion -->
  //"33" -> 33
  //"33a" -> NaN(not a number)
  //true/false -> 1/0
  //Number,Boolean,String need to check with typeof 



  ------------------------------------------------------------------------------------------------------------------------------------------------

  INTERVIEW PRESPECTIVE

    Primitive & Non Primitive

    Primitive 
 Number ,  String  , Boolean , null(empty) , undefined , Symbol (make any value unique) , BigInt 

   Non Primitive or Refernce 
  Array , Objects , Functions 

  Assignment1 :- make examples of each and write it again also understand each datatypes typeof