# COMON JAVASCRIPT QUESTION

JavaScript is the world most popular lightweight, interpreted compiled programming language. It is also known as scripting language for web pages. It is well-known for the development of web pages, many non-browser environments also use it. JavaScript can be used for Client-side developments as well as Server-side developments.

## What are the differences between Java and JavaScript ?

>JavaScript: It is a light-weighted programming language (“scripting language”) and used to develop interactive web pages. It can insert dynamic text into HTML element. JavaScript is also known as the browser’s language.

>Java: Java is one of the most popular and widely used programming language. It is an object-oriented programming language and has a virtual machine platform that allows you to create compiled programs that run on nearly every platform. Java promised, “Write Once, Run Anywhere”.


## What is DOM?

DOM stands for Document Object Model.

DOM is a programming interface for HTML and XML documents.

When the browser tries to render a HTML document, it creates an object based on the HTML document called DOM. Using this DOM, we can manipulate or change various elements inside the HTML document.

## What are JavaScript Data Types ?

There are three major Datatypes in JavaScript.
1. Primitive
    - Numbers
    - Strings
    - Boolean

2. Trivial
    - Null
    - Undefined
3. Composite
    - Objects
    - Functions
    - Arrays


## What is Scope in JavaScript?  

In JavaScript, each function gets its own scope. Scope is basically a collection of variables as well as the rules for how those variables are accessed by name. Only code inside that function can access that function's scoped variables.

A variable name has to be unique within the same scope. A scope can be nested inside another scope. If one scope is nested inside another, code inside the innermost scope can access variables from either scope.


## What is ‘this’ keyword in JavaScript ?

this’ stores the current execution context of the JavaScript program. Thus, when it used inside a function, the value of ‘this’ will change depending on how the function is defined, how it is invoked and the default execution context.

## Explain Null and Undefined in JavaScript  
Something hasn't been initialised : undefined.
Something is currently unavailable: null.

##  What is Coercion in JavaScript?  

Refers to the process of automatic or implicit conversion of values from one data type to another. This includes conversion from Number to String, String to Number, Boolean to Number etc. when different types of operators are applied to the values.


## What is the definition of a Higher-Order Function?
A higher order function is a function that takes a function as an argument, or returns a function. Higher order function is in contrast to first order functions, which don’t take a function as an argument or return a function as output.

## Could you explain the difference between ES5 and ES6  

ES5 is also known as ECMAScript 2009 as it is released in 2009. It is a function contractors focus on how the objects are instantiated. For ES5 you have to write function keyword and return, to be used to define the function, like normal general JavaScript language.

ES6 is also known as ECMAScript 2015 as it is released in 2015. Its class allows the developers to instantiate an object using the new operator, using an arrow function, in case it doesn’t need to use function keyword to define the function, also return keyword can be avoided to fetch the computer value. 

## What are the differences between ES6 class and ES5 function constructors?  
  ES6 class constructors
  ES6 class constructors creates objects by adding function to their prototypes (Blueprint).it ensures that this keyword used by the developer is referring to the object being created by the developer. Its syntax is similar to object creation in other object-oriented programming languages.

ES5 function constructors
ES5 function constructors also create objects along with inheritance property. Any function can be used as a function constructor and it primarily focuses on the creation of reusable object creation code.This also uses a new operator for object creation but focuses on how the objects are being instantiated.

## Describe the JS module design pattern  

The Module Pattern is one of the important patterns in JavaScript. It is a commonly used Design Pattern which is used to wrap a set of variables and functions together in a single scope. It is used to define objects and specify the variables and the functions that can be accessed from outside the scope of the function.

## What are callbacks?
A callback is a function that will be executed after another function gets executed.

In javascript, functions are treated as first-class citizens, they can be used as an argument of another function, can be returned by another function and can be used as a property of an object.


## What is the use of a constructor function in javascript?

Constructor functions are used to create objects in javascript.

When do we use constructor functions?

If we want to create multiple objects having similar properties and methods, constructor functions are used.

## What are classes in javascript
classes are nothing but syntactic sugars for constructor functions.They provide a new way of declaring constructor functions in javascript.

## What is memoization?
Memoization is a form of caching where the return value of a function is cached based on its parameters. If the parameter of that function is not changed, the cached version of the function is returned.

## What are arrow functions?
Arrow functions were introduced in the ES6 version of javascript.They provide us with a new and shorter syntax for declaring functions.Arrow functions can only be used as a function expression.

## What is the use of promises in javascript?
Promises are used to handle asynchronous operations like server requests


Promise object has four states -

Pending - Initial state of promise. This state represents that the promise has neither been fulfilled nor been rejected, it is in the pending state.
Fulfilled - This state represents that the promise has been fulfilled, meaning the async operation is completed.
Rejected - This state represents that the promise has been rejected for some reason, meaning the async operation has failed.
Settled - This state represents that the promise has been either rejected or fulfilled.

>Reference: https://github.com/sudheerj/javascript-interview-questions