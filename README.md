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

- A function in JavaScript is ...

- functions help you split your program into small, repeatable blocks of code

- There are **3** types of functions in JavaScript based on the way they are declared ( + they also have slight differences in the way they can be used in programming):

  - **function declarations**
  - **function expressions**
  - **Fat arrow functions** (newest type)

- Example:

  ```javascript
  
  ```

##### What is the difference between function expression, fat arrows and function declaration?

- **Function declaration**

  ```javascript
  
  ```

  

- **Function expression**

  ```javascript
  
  ```

  

- **Fat arrow functions** ( => )

  ```javascript
  
  ```

  

#####  What is an immediately-invoked function expression (aka IIFE) ? Why use it?

-  What is it?  **Immediately-invoked function expressions** are a sub-type of function expressions which are **called ONLY ONCE**, which happens **immediately after they are initialised** 

- As with other function expressions, IIFEs can be assigned to a variable

- **Usage:** IIFEs are used when you want to enclose certain variables in a function scope and you will not be using them anywhere else in the program

- **Example:**

  ```javascript
  const isIIFE = (function(a){
    console.log('This is an + a')
  })('IIFE');
  ```

  
### Scope/Closure Questionnaire

-------



#### Learning Objectives

- Explain what is scope and what defines it.

- Demonstrate the difference between var and let.

- Explain what hoisting is, what is hoisted and what not.

- Demonstrate how each of the three function type is hoisted.

- Explain what is closure and how it's connected to scopes.

- Demonstrate how to provide access to a variable's value outside the function it is defined in.

- In a given piece of code, determine if closure exists and identify it.

  

#### Theoretical Questions 

##### What is scope? Provide an example.

- 

- **Example:**

  ```javascript
  
  ```

##### What is the difference between const, let and var?

- these are all different ways to declare  a variable (in JS there is no str, string, num, double, char, float, etc.)
- var is **NOT RECOMMENDED**
- since ES6, **let** and **const** are used with all different variable types
- **const** is used for variables which will not be changed in the program, i.e. you cannot reassign it while you may do so with **let** (even though it is not good practice)
- difference in their **scope**: 
  - **var** has **function scope**, i.e. it is visible across the whole function, in which it is defined
  - **let** and **const** have **block scope**, i.e. in between curly braces {} and they are not visible outside it

- difference in **hoisting**:
  - All variables are **hoisted** in JS because unlike common opinion, JS is "scanned", i.e. it has **just-in-time compilation**
  - however, var- declared variables appear as **undefined** and let and const **throw an error** as the variables are in **TEMPORAL DEAD ZONE** **(TDZ)**

#####  What is the difference between == and ===, and what is type coercion?

- **===**  is referred to as **"strict equal"**, i.e. it compares both the **value** and **type** of both sides
- **==** compares **only the values** 
- they both return a **boolean**, i.e. true/false
- **type coercion** refers to 

##### What is variable and function hoisting?

- **hoisting** refers to the idea that
- 

##### What is hoisted and what is not?

- **everything** is hoisted in theory in JS
- 
- 

##### What is lexical scope? What is lexing-time?

- **lexical scope** refers to the scope that is physically around a variable
- **lexing-time**

##### What is closure? Provide an example.

- **closure** refers to the idea 

- ***Example:***

  ```javascript
  
  ```

  



###### Created by Kamelia Bujuklieva.
###### July 2021, Sofia, Bulgaria
