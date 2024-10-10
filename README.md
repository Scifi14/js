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

confidence is everything 
conversions and operations 

let score = 33

when declare variable , we work at backend 
we want to know its type
person send us value but it come through form 
possible that it stored in string and its not number 

sometimes we do not know from where value come from 

sometimes we take value from frontend
const {score}=  req.body //in this there is no gurranty that its a number or what 

we can know its type 
console.log(typeof(score))
console.log(typeof score )

if our value come in string and we want to perform operation on numbers 
let value = Number(score)  //now score is converted to numbers

NaN is not in number
if we convert 33abc which is in string to number we get NaN as output 
it get converted but NaN comes 
NaN is special type , check if in value its this not given 

this is some issue in js thats why people use typescript  as its not strict check 

if value is null and we covert to Number we get answer 0 
if value is undefined and we covert to Number we get answer NaN
if value is boolean in true when convert to Number we get answer 1
in false we get 0
in case of string as not able to convert to Number we get NaN

in conversion to Number 
//"33" = 33
"33abc"= NaN
true = 1
false = 0

we convert 1 as number to Boolean we get output true 
if we convert ""  to Boolean we get output false 
if we covert "as" a string to Boolean we get output true 

in conversion to Boolean we get 
1 as true 
0 as false 
"" as false 
hitesh as true 

when convert a number to String, it might look as number but when do typeof we realize its a string 

other conversion possible as objects , array etc 

operations
let value = 3
let neg= -value

(2*2)
(2**3)
(2/3)

let str2="as"
let str3="ad"
let str = str2 + str3


problem come 
console.log("1"+2)
console.log(1+"2")
console.log("1"+2+2)
console.log(1+2+"2")
there are some ecmascript guidelines 
that when to convert what are the guidelines
in real life use parenthesis 
code will not merge in industry if do these things 


console.log(+true)  //1
console.log(+"")  //0

operator precedence read but for exam only 
num1 = num2 = num3 = 2+2
in code, readability is main thing 

precedence operator 
prefix = 
postfix = 
see in js and mdn 

comparisons of datatypes
(2>1)
(2>3)
answer come in boolean value

problem come when comparisons happen bw diff datatypes
"02">1
"2">1

comparisons not give you predictable results 

when compare make sure that compare with same datatypes
in typescript make sure that you, do not compare diff datatypes
typescript gives you strict rules 

in diff datatypes , 

in null value convert 
predictable result not come 

equality check and comparisons work differently bcz 
comparisons convert null to number treating  it as 0
thats why (3) null >= 0 is true 
and 
(1) null > 0 is false 

(null>0) //false
(null == 0) //false
(null >=0) //true 
(undefined == 0) //false
(undefined > 0)  //false
(undefined < 0) //false
comparisons and equality check are diff things

strict check means it checks strictly with === , it checks value but strictly  but with datatype

("2" === 2) //it check datatype also //false 

clean code is valuable 

datatypes 
in official document 
two types 
1. primitive 
2. non primitive 

diff is 
 call by value and call by difference
diff is how data store and how you can access in memory

primitive datatype 
7 category 

string , number , boolean , null, undefined , Symbol , BigInt
to make value unique we use symbol 

//reference type (non primitive)
Array , Objects 

Objects and Browser events master this for master js 
we do not have to define type in js 
in typescript you have to mention
const score:number =100

we can do manually too 

with symbol even if pass same value its output will not be same 
const id = Symbol('123')
const anotherId = Symbol('123')

console.log(id===anotherId) //false 

for bigger number bigInt use 
for that put n in number 

we can treat function like variable in js 
const myFunction = function(){
    console.log("hello")
}

typeof  datatype for null is obect 
and for function is object or function object
non primitive return type datatype is function 

stack and heap memory 

in starting languages,  to save memory and reserve , it was our job as programmer 
in moder language we do not get most memory control ,there is garbage collection etc

there are two types of memory / datatype available 
primitive and non primitive typeof

memory are here of two type
stack and heap memory
where primitive type , stack memory use 
where non primitive type , heap memory use 
when stack memory use the variable we declare we get a copy
when memory define in heap , you get reference of origional value

one upon one is stack 
heap 

let name="hit"
let another = name 
another= "chai"
console.log(name)
console.log(another)


let userO ={ email:"iser@f.com",
up1:"iser#f"}
let userT =userO
userT.email="hits"

all primitive values go in stack and in stack we get copy 
all non primitive values go in heap and in heap we get reference(means whatever change is done in original value)
