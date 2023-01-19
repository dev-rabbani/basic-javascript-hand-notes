# Basic Javascript

### Basic Conecpts

  ### Console
  console.log() ==>> Prints the element in an HTML Like tree.
  console.dir() ==>> Prints the element in a JSON Like tree.
  
  ### JS Comments
  // Single Line Comments
  /*
    This is mulit line
    Comments
  */


### 06. JS Variables 
  var name = "Golam Rabbani"
  
   Here..
   var = keyword,
   name = variable name,
   value = "Golam Rabbani"
   
   varible Naming Convention:-
   https://www.w3schools.com/js/js_variables.asp
   
   
 ### 07. Js Reserved Word
    For Reference :_
    https://www.w3schools.com/js/js_reserved.asp
    
### 08. Js Data Types
    
    Mainly Two Types:-
    (1)Primitive Types : Primitive Types are defined by Javascript.
    (2)Object Types : Object Types are defined Data type.
    
    ### 1.Primitive Data Type -
    
      a. Number
      b. String
      c. Boolean
      d. Undefined 
      e. Null
      
    ### 1.Object Type -
      
      a. Array
      b. Object
      c. Function
      
    ### Shortly
    
    Data Types:-
    1. Number (1234)
    2. biInt  (1234567895n)
    3. Boolean (true/false)
    4. String ("strign")
    5. Undefined 
    6. Null 
    7. Object

  *** Normal Number range min -(2^53 -1) and max (2^53-1).
      
### 09. Js Number
  
      Number Literal:-
      var num = 1234
      
      Number Constructor:-
      var num = Number(1234)
      
      noted: 
      
      # 1/0 Return Infinity
      # If Type Not Match, Return NaN(Not A Number)
        'abc' * 100 = NaN
      
### 10. Js String (''/"")
  Anything Wrapped between quotes are called string
  
      String Literal:-
      var str = "1234"
      
      String Constructor:-
      var str = String(1234)
      
### 11. Js Boolean
  A JavaScript Boolean represents one of two values: true or false.
  
      True =>> Return 1
      
      False =>> Return 0

### 12. Js Null & Undefined

  Undefined: A variable without value always stroe undefined.
  
  Null: A variable with unknown value can stroe null.
  
  *** Null is a special type used as a absence of an object.
  
  ### 13. Js Type Conversion
  
    1. Implicit Conversion: In certain situation, Javascript automatically converts one data type to another (to the right type) . This is known as implicit type conversion.
    2. Explicit Conversion: You can also convert one data type to another as per your needs. The type conversion that you do manually is known as explicit type conversion.
    
    For Reference:
    https://www.programiz.com/javascript/type-conversion
    
    ### Truthy / Falsy Value--
    
    Falsy Value- 
    a. '' (Empty String)
    b. 0  (Zero)
    c. Null 
    d. Undefined
    e. NaN
    f. false
    
    *** Otherwiser all are truthy Value..
    
### 15. Js Operators

  1. Arithmetic Operator:
    +, -, *, /, %, ++, --
    
  2. Assignmnet  Operator:
    =, +=, -=, *=, /=, %=

  3. Comparison  Operator (Return Boolean) :
    ==, !=, >, <, >=, <=, ===, !==
    
  4. Logical Operator 
    &&, ||, !
    
  5. Typeof Operator
      typeof
    
### 17. Js Math Functions
    
    var num = 4.589;
    
    a. Math.abs(num)  return 4.589;
    b. Math.floor(num)  return 4;
    c. Math.ceil(num) return 5;
    d. Math.round(num) return 5;
      Math term a calculation feedback like as 4.5 = 5, 4.4 = 4, 4.8 = 5;
    e. Math.max(100,200,300) return 300;
    f. Math.min(100,200,300) return 100;
    g. Math.pow(2,4) return 16;
    h. Math.sqrt(64) return 8;
    i. Math.randorm() return random number each call;
       if we need less than 50-
       Math.random()*50+1;
       For int value =>> Math.floor(Math.random()*50+1;) or use pareInt
      
### 18. Js Date Functions
  
  For Refercence:
  https://www.w3schools.com/js/js_date_methods.asp
  
### 20, 21, 22. JS Logic & Condition
  
  if, if else, else if , nested else if...
  
  For Reference :
  https://www.w3schools.com/js/js_if_else.asp
  https://javascript.info/ifelse
  https://www.programiz.com/javascript/if-else
  
### 24. JS Switch Statement 

  For Reference:
  https://www.programiz.com/javascript/switch-statement
  
### 25. JS Logical Operator
  
  &&, ||, !
  
  For Reference: 
  https://javascript.info/logical-operators
  
### 26. JS Ternary Operator:
  
  condition ? true block : false block;
### 27. Shorthand (&&  /  || )

For Reference:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_AND

### 28. JS Loops

  Loops are statemnet which execute some blocks of code repeatedly untill the condition becomes false.
  a. For Loop: 
  for(initialization; condition; steping){
    Block
  }
  b. While Loop:
  while(condition){
    block
  }
  c. Do While Loop: 
  do{
    block
  } whtile(condition) {
    block;
    steping;
  }
  
  For Reference:
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration
  
  
    
    
  
