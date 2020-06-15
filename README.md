# what-i-learned-in-week-4

## Variable *Let* and *Const*
* ***let*** allow variable tobe changable
* ***Const*** doesn't allow variable tobe changable. ***Const*** is also the recommended option.

## Boolean is the type of code that gives back the value *true* or *false*
#### Boolean condition syntax: 
* **&&** and
* **||** or
* **!** not/opposite
* **===** exactly equal
* **!==** not equal

#### Example:
~~~
let hungry = true;
let haveMoney = true;
function shouldBuyFood() {
return hungry && haveMoney
}
shouldBuyFood(); //true
~~~
## String properties
* **string.length**: get how many letter in that string
* **string.toUpperCase()**: to capitalize that string
* **string[1]** or **string.charAt[1]**: target index 1 in a string to return a letter of index 1
* **string.getIndex['b']**: target letter b in a string to return that letter's index
* **Number('123')**: convert string to number

#### Example:
~~~
//get last letter in a string

function getLastLetter(str) {
return str[str.length -1]
}

getLastLetter('Hello'); //o
~~~

