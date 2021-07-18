
### Functions/Exceptions Questionnaire

-------



#### Learning Objectives

- Explain what functions are and why they are so important.
- Write a function that accepts parameters and produces a result.
- Name the three types of functions and explain their differences.
- Demonstrate writing functions that are single-responsible.
- Explain what exceptions are and how we handle them?
- Handle an exception that is thrown inside a function.

#### Theoretical Questions 

##### What is a function? What types of functions are there?

- functions are first-class citizens in JS, i.e. they are very crucial to the language; they are of type object

- functions can be accepted as parameters to another function, can be assigned to variables, can be returned from a function, and can also have properties and methods of their own

- functions are procedures that perform a certain task (analogically to verbs in a sentence); they help make your code more reusable and broken down into smaller pieces

- functions help you split your program into small, repeatable blocks of code; functions usually take one or more parameters and return some data; functions need to first be defined and then called, so that they can be executed in the program

- when **defining** a function, you have **parameters**, while when **calling** a function, you have **arguments**

- functions in JS can have **default parameters**, which are used as arguments if no argument or 'undefined' is passed

- function in JS can use the **rest operator (...)** as a parameter thanks to which we may pass **an indefinite number of arguments,** which will come as an **array**

- Functions **must always return something**; if it is not *explicitly* specified, they return **undefined**

- There are **3** types of functions in JavaScript based on the way they are declared ( + they also have slight differences in the way they can be used in programming):

  - **function declarations**
  - **function expressions** - they are assigned to a variable; 
  - **Fat arrow functions** (newest type sinece ES2015/ ES6)

- Example:

  ```javascript
  //function declaration
  function firstLetter (name) {
    return name[0]
  }
  //function expression 
  const nameLowerCase = function (name) {
    return name.toLowerCase();
  };
  //fat arrow function
  const nameCaps = (name) => name.toUpperCase();
  ```

##### What is the difference between function expression, fat arrows and function declaration?

- **Function declaration**
  - function keyword, function name, input parameters (optional), function body, return value;

- **Function expression**
  - again has the function keyword but instead of a name, it is assigned to a variable

- **Fat arrow functions** ( => )

  - No ***function keyword***, again assigned to a variable
  - no ***arguments*** object
  - no ***this*** context

#####  What is an immediately-invoked function expression (aka IIFE) ? Why use it?

- What is it?  **Immediately-invoked function expressions** are a sub-type of function expressions which are **called ONLY ONCE**, which happens **immediately after they are initialised** 

- As with other function expressions, IIFEs can be assigned to a variable

- **Usage:** IIFEs are used when you want to enclose certain variables in a function scope and you will not be using them anywhere else in the program

- **Example:**

  ```javascript
  const isIIFE = (function(a){
    console.log('This is an + a')
  })('IIFE');
  ```

  




###### Created by Kamelia Bujuklieva.
###### July 2021, Sofia, Bulgaria
