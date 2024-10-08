# js
confidence is everything 
js executes on browser 

question is what type of question should come to our mind 

every software that is comiler know that which file to expect and what to do with that code like .js or .txt file 
in case of js it was in browser 
now js used in everything 
and its environment is nodejs  that can run our js 
there are diff type of execution engine like v8 for browser 
and there is denojs as well


github 
(for low configuration or use on diff computers )
use codespaces

go to file -> view -> command palete write container ->  show all definations -> node js and javascript 
click ok 

go to 4 icon and add that file , commit and push 



# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
#
# On branch main
# Your branch is up to date with 'origin/main'.
#
# Changes to be committed:
#	modified:   README.md
#
go to codespaces and delete the running machine 

why want to learn js 
(learn bcz want to build something )
everything is play of mindset 
perpective is everything 

to store something we need memory space 
constant we not change 
and variable we can change 

learn by investigation 

const accoutId

at the end goal is name should be readable

const means it can not be changed 

we can change but it will get analyzed by nodejs 
and it will reject it 

when we write with // , nodejs will not read it or not execute it 

with let and var we can change variable name 
to declare variable in js there is two way , let and var 
in js there was a problem it does not know what was scope , scope is {}
so var had this problem so if there was two variable with same name in dif scope it was not able to identify which is which 
so not use var bcz of issue in block scope and functional scope

now with let it can identify , there is not problem of scope 

new type comment 
/*

 */

in js its safe language , we can declare a variable without  let and var and reserve memory

what if we want not to assign value to variable 
js consider it undefined


console.table with [] we can write all variable name 

(programming should be done , by keyboard practice and practice overhere )
datatypes and ecmascript
in js written in books is diff than today's js 
in old js there was classes , module , arrow function was not there but now its there 
lot of code written in old way 
js does not want that old code that waste bcz you are using new code
and u are using new code then everything should get a standard that treat entire code as new code 
bcz after all entire code will run through engine 
in js inside double quoutes you write use strict
it means entire js code will treat as newer version
there is no way use no strict , once written your code will treat from newer standards through engine 

 now generally everything run in strict mode , no need to write this 
 its good syntax

 alert statement 
 example alert(3+3)
 in browser it can run
 but in node to use there is diff syntax

when we can use spacing 
in js we avoid ;

console.log(4) console.log(3)
in above line error show 


console.log(4); console.log(3)
now error removed

 code execute does not means, its fine 
 it should be readable , future proof 
 otherwise what's there for experience 
code readability is priority 

extension like prettier which indent automatically

documentation mdn is from mozrilla 

ecmascript(ec39)
see its specification
in js in starting days every browser has diff standards 
everyone thought sit together and define a single organiztion which write standards
not js but its standards
ex writing loop this is how input take and this output give 
in standards there are priority algorithms that if this come , give output in this way otherwise that way

lot of datatypes in js 
global object etc 
let age ="hit"  //string 
let age = 5 //number
ler isL = false //boolean
//symbol when want to tell about unique(figma tools use this )
//object 

bigint generally used in stock trading 

null is standalone value , (null is representation of empty value )
undefined when value not defined, but declared variable

let state = null
let state;

typeof used to know which type of variable is 

typeof null is object
typeof undefined is undefined (bcz its type in js)
some people say its error of js 

