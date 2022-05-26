# Class 6 Javascript

JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.

---

### Standard objects

- Get to know standard built-in objects Array, Boolean, Date, Error, Function, JSON, Math, Number, Object, RegExp, String, Map, Set, WeakMap, WeakSet, and others.

### Expressions and operators

- Learn more about the behavior of JavaScript's operators instanceof, typeof, new, this, the operator precedence, and more.

### Statements and declarations

- Learn how do-while, for-in, for-of, try-catch, let, var, const, if-else, switch, and more JavaScript statements and keywords work.

### Functions

- Learn how to work with JavaScript's functions to develop your applications.

---
## Javascript Variables

4 Ways to Declare a JavaScript Variable (declare means to write the variable)

1. Using var
2. Using let
3. Using const
4. Using nothing

## What are Variables?

- Variables are containers for storing data (storing data values).

In this example, x, y, and z, are variables, declared with the “var” keyword:

       Var x = 5;
       var y = 6;
       var z = x + y;

In this example, x, y, and z, are variables, declared with “let” keyword:

       let x = 5;
       let y = 6;
       let z = x + y; 

In this example, x, y, and z are undeclared variables:

       x = 5;
       y = 6;
       z = x + y; 

---

## var - When to Use JavaScript “var”?

- Always declare JavaScript variables with var, let, or const.
The “var” keyword is used in all JavaScript code from 1995 to 2015.
The “let” and “const” keywords were added to JavaScript in 2015.
If you want your code to run in older browser, you must use var.

## const - When to Use JavaScript “const”?

- If you want a general rule: always declare variables with “const”.
If you think the value of the variable can change, use “let”.
In this example, price1, price2, and total, are variables:
Example

       const price1 = 5;
       const price2 = 6;
       let total = price1 + price2;


[Back to Reading Notes](https://tomgtaylor.github.io/reading-notes)