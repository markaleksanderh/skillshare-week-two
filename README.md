# Week Two

## Goals
1. Understand the basics of JavaScript.



We won't need to setup anything this week.

Though it's possible to build complete webpages without JavaScript, JavaScript is fundamental to ...




As I mentioned last week, the first thing we learn in any language is the _Hello, World!_ program.

### Using the console

We'll use the console here to print output 
In practice, the console is invaluable when debugging an application.

```
console.log("Hello, World")
```

### Variables

Until recently in JavaScript it was only possible to declare variables using the keyword `var`.


#### `var`

Weakest assignment.

When we reassign the variable, we don't need to include the keyword `var`; we just type the variable name again.

```
var x = 5
console.log(x)

x = 10
console.log(x)
```

In some languages, e.g. Python, you don't need to add the `var` at all.


#### `let`

May or may not be reassigned.

`let`

#### `const`

JavaScript now supports two other declarations; `let` and `const`.

`const` indicates the variable is a constant and that the value will not be reassigned throughout the program. `const`s should be declared at the top of your program and can be declared in capitals.

```
const VAT_RATE = 0.2
```

Attempting to reassign the value of a constant will cause a `TypeError` error.

```
const VALUE_OF_PI = 3.142

console.log(VALUE_OF_PI)

const VALUE_OF_PI = 3.14159
```


#### Data types

A note on types. JavaScript is what's called a weakly-typed language, meaning you don't need to declare what _type_ of value will be stored in a variable.

JavaScript is a very forgiving language and it's acceptable to do the following:

```
var weekday = "Monday"
weekday = 0
```

Other languages, such as C or Java are strongly-typed which means you have to declare the type of value stored in the variable.

```
int speakerPin = 6;
float c_frequency = 65.41;
```

The data types we'll cover for this week will be:

- `string` - a text string, e.g. `"Hello, World!"`.
- `number` - JavaScript doesn't distinguish between integers and floating point numbers.
- `boolean` - either `True` or `False`.

#### Best practice

To make your life easier (and for the sake of anyone else reading your code), your variable names should be refer to the sort of value you're storing in the variable.


Arrays

For loops

Functions

Arrow functions

Conditionals

Objects












