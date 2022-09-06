# JavaScript DataStructure and Algorithm

## Arrays
Descriptions


`arrayname.push()` is used to add element at the end of an array

Example:

`arrayname.pop()` is used to remove element at the end of an array and that value can be stored in a variable or being used elsewhere in program

Example: 

`arrayname.shift()`is used to remove the first element from an array.

Example:

`arrayname.unshift()` is used to add element at the first index of an array

Example:

==================================================================================
## Functions
Functions are used to create reusable codes

Example and syntax:

```
function functioname(param1, param2) {
  console.log(param1, param2);
}

// calling function
functionname()
```
### Parameters and Arguments
`parameters` are variables or value which is used when defining function

`arguments` are value or variables used when calling functions

### Variable Scope

varriable can be declared using `let`, `var` and `const`.

`var`: varibale declared with var can be declared again with or without the some value. not good to use it cause it can cause confusion in program.

`let`: let is the some as var except that you can not declare the some variable with the soome name using `let` keyword. good to use in Javascript.

`const`: this keyword i used to declare constant variable in the program.

`declaring variable outside the function act as global variable, and declaring variable without var, let or const keyword act as global variable`.

### undefiened returned by a function

a function can return an undefiened value when it doesnt not have returned value and it has been called.

Example:

```
let sum = 0;

function addSum(num) {
  sum = sum + num;
}

addSum(3);
```




























