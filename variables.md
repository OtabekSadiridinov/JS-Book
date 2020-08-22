# Variables and Types
Like almost every dynamic language, JavaScript is a "duck-typed" language, and therefore every variable is defined using the ``var`` keyword, and can contain all types of variables.

We can define several types of variables to use in our code:

```js
var myNumber = 3;                   // a number
var myString = "Hello, World!"      // a string
var myBoolean = true;               // a boolean
```
A few notes about variable types in JavaScript:

- In JavaScript, the Number type can be both a floating point number and an integer.
- Boolean variables can only be equal to either true or false.
There are two more advanced types in JavaScript. An array, and an object. We will get to them in more advanced tutorials.

```js
var myArray = [];                    // an array
var myObject = {};                  // an object
```
On top of that, there are two special types called ``undefined`` and ``null``.

When a variable is used without first defining a value for it, it is equal to undefined. For example:

```js
var newVariable;
console.log(newVariable); //prints undefined
```
However, the ``null`` value is a different type of value, and is used when a variable should be marked as empty. ``undefined`` can be used for this purpose, but it should not be used.

```js
var emptyVariable = null;
console.log(emptyVariable);
```
will print out ``null``

## Exercise
You must define the following variables:

1. A number called myNumber which contains the number ``4``;
2. A string called myString which contains the sentence ``Variables are great.``;
3. A boolean called myBoolean which contains the value ``false``;
