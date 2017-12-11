### Javascript Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Name some of the data types in Javascript.
null, undefined, boolean, string, integer


  //Googled Answer: Six data types that are primitives:
Boolean.
Null.
Undefined.
Number.
String.
Symbol (new in ECMAScript 6)


#### 2. Describe what "if" does in Javascript.

  //Your Answer sets condition that if something meets it, it continues to run that code


  //Googled Answer: The if/else statement executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed. The if/else statement is a part of JavaScript's "Conditional" Statements, which are used to perform different actions based on different conditions.


#### 3. Write a function that takes one number as a parameter and decides if that number is divisble by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisble by three".

function threeDivisor(num) {
  if (num % 3 === 0) {
    return num + " is divisible by three"
  } else if (num % 3 > 0) {
    return num + " is not divisible by three"
  } else {
    return num + " is not a number"
  }
}

#### 4. What is JSON?

  //Your Answer: stands for Javascript object notation


  //Googled Answer: JSON (JavaScript Object Notation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate. It is based on a subset of the JavaScript Programming Language, Standard ECMA-262 3rd Edition - December 1999. JSON is a text format that is completely language independent but uses conventions that are familiar to programmers of the C-family of languages, including C, C++, C#, Java, JavaScript, Perl, Python, and many others. These properties make JSON an ideal data-interchange language.

#### 5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.

var sharon = {
  dateOfBirth: "09121974",
  hair: "red",
  hobbies: ["billiards", "beach", "reading"]
}

#### 6. What is a closure?

  //Your Answer: A closure helps bring a variable out of a function, doesn't change the initial value


  //Googled Answer: A closure is an inner function that has access to the outer (enclosing) function's variables—scope chain. The closure has three scope chains: it has access to its own scope (variables defined between its curly brackets), it has access to the outer function's variables, and it has access to the global variables.

#### 7. What's the difference between =, ==, and === in JavaScript?

  //Your Answer: = is equal to, == is partially equal, a string of "5" and an integer 5 would come as true, === is absolutely equal, integers cannot equal strings


  //Googled Answer: JavaScript has both strict and type-converting equality comparison. For strict equality the objects being compared must have the same type and:

Two strings are strictly equal when they have the same sequence of characters, same length, and same characters in corresponding positions.
Two numbers are strictly equal when they are numerically equal (have the same number value). NaN is not equal to anything, including NaN. Positive and negative zeros are equal to one another.
Two Boolean operands are strictly equal if both are true or both are false.
Two objects are strictly equal if they refer to the same Object.
Null and Undefined types are == (but not ===). [I.e. (Null==Undefined) is true but (Null===Undefined) is false]


#### 8. Create an array with at least 4 items inside it, then access two of the values and console.log() them. Try to access the two values in two different ways.

var colors = ["red", "orange", "blue", "green"]
console.log (colors[0])



#### 9. Describe the different kinds of loops and why you would use them.

  //Your Answer: while, for


  //Googled Answer: Loops offer a quick and easy way to do something repeatedly.
A for loop repeats until a specified condition evaluates to false. The do...while statement repeats until a specified condition evaluates to false. A while statement executes its statements as long as a specified condition evaluates to true.

#### 10. How would you explain "scope" in javascript?

  //Your Answer: Scope relates to if something is within a function. Is a variable is within a function, it is part of a local scope. If it's outside of any function, it is a global scope.


  //Googled Answer: declared outside of a function belongs to the global scope, and is therefore accessible from anywhere in your code. Each function has its own scope, and any variable declared within that function is only accessible from that function and any nested functions.
