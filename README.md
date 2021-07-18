### Scope/Closure Questionnaire

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

  


###### Created by Kamelia Bujuklieva.
###### July 2021, Sofia, Bulgaria
