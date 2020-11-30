# how are you world?
it's like [hello world](https://github.com/rsninja722/helloworld) but I am continuing the small talk with world


## code explanation

# setup
make variable msg an empty string

# add letters to msg individually
## H
get "H" by makeing a string from char code 72, add it to msg from within a try,catch,finally block, within an immediately invoked function

## o
get the text of the html body tag, and get the character at index 2, which is "o"

set msg to itself concatenated with the "o"

## w
create an array with the first element being a function, and call it

the function gets its own code as a string, then gets the "w" from the function name - addw

## space
create an object and define a setter that looks it self up, converts its code to a string, then adds the space between { and msg to the msg. it also warns what ever you set it to in the console

every time a space is needed, spacer.space is set to something

## a
make a function that returns "constructor", then set c to "constructor". Get constructor of "constructor" which is a string, then get that constructor, which is a function, then use that to add to the String prototype a function that returns "a". the function is created with "new Function" because Brendan Eich hates us all 

msg is set to itself + [] which is treated as an empty string + a string with returnA called on it

## r
make an array with msg in it and call map on it, which basically passes msg into the arrow function

"r" is from the name of console.warn at index 2. "r" is then accessed at index 0 twice. The first 0 is made by subtracting 6 from the length of "Object". The second 0 is made by seeing if "Array" ends with "stupid js" which is false, then false is hinted to be a number (0) with the +

## e
function e creates an e property with a value of 1 ( 1 comes from !undefined as a number) in itself if it doesn't exist. It increments e and returns it

the E method is created in e which returns a character from a char code

e is called while the char code of e.e is not "e"

"e" is then added to msg

## space
same as the first space

## y
add to the Number prototype a method that adds its parameter to msg

class a is created with a constructor that takes in and stores c, and a static method that returns "y". It does this by getting the script text, getting the line at index 51, then getting the character at position 3, which is the "y" from the comment `// y`

class b which extends a is created. Its constructor just calls a's constructor. b has a getter that returns "y" by calling the static method from class a

an instance of class b is created with b passed into the constructor so `this.c` is class b, which has the static method from a

Not a Number is created by turning a string into a number. Not a Number has the Number prototype so addToMsg can be called on it with d.y passed in

## o
a big chain of prototypes eventually calls toString on one of the prototypes, which returns "[object Undefined]". An array is created with Array.from which makes an array of the characters of "[object Undefined]". The "o" is sliced into an array and passed into addToMsg. ["o"] is treated the same as "o" when being added to the msg

## u
`eval("Number.__proto__")` returns function () { [native code] }, an empty array is added to it to make it a string, and the second character is accessed and added to msg.

## space
same as the first space

## w
no

## o
get o from Error as a string, then call bruh to return a function used as a template literal tag, which adds the arguments of the template literal ( o and msg)

## r
create a generator which will yield the return value of another yield. It is obfuscated by being in an object with a computed property name, then being accessed and called. the generator gets next called, the again with a value of true passed in. The first yield returns the return value of the second yield in an object, g is then assigned this object, obfuscated by destructuring assignment with a default value. An iterator is defined for g, which will add the r from true to msg by creating an array of the letters of msg and the r, then joining them back together, then the iterator will return that it is done. The iterator is run by the for...of loop inside of a bunch of unnecessary control flow. All of this is in a block.

## l

## d

## ?

# showing msg

a new canvas is added to the document

the context of the canvas is stored and the font is set

msg is split in "" which makes an array with every character being a separate element. A for of loop is used to go through these characters

in the loop the letter is drawn at the x position stored in the ctx stroke style, then the x position is increased by 9.