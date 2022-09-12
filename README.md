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

### Equality, strict inequality and strict inequarity operators (==, ===, != and !==)

`type coerscion`: javascript ability to convert from one datatype to onother in comparission

Example:

```
1   ==  1  // true
1   ==  2  // false
1   == '1' // true
"3" ==  3  // true
```

`strict operator` `===` this is the opesite of coersion, because it doesn't convert from one type to another

Example:

```
3 ===  3  // true
3 === '3' // false
```

Like the equality operator, the >, <, >=, <= will convert data types while comparing.


## Logical Operators AND (&&), OR (||)

`AND` operator return True when All Operands are True while `OR` operator return True when one of the operands is true


### Return on Objects and switch



'
'
'

### Testing objects for Property

`.hasOwnProperty(propertyname)` is used a method that is used to check if the object has that property name.

#### Example:

```
const myObj = {
  top: "hat",
  bottom: "pants"
};

myObj.hasOwnProperty("top");
myObj.hasOwnProperty("middle");
```

### Manipilating Complex Objects

#### Example
```
const ourMusic = [
  {
    "artist": "Daft Punk",
    "title": "Homework",
    "release_year": 1997,
    "formats": [ 
      "CD", 
      "Cassette", 
      "LP"
    ],
    "gold": true
  },
  
    {
    "artist": "Punk",
    "title": "Lazy",
    "release_year": 1987,
    "formats": [ 
      "CD", 
      "USB"
    ],
    "gold": False
  }
];
```

### Accessing nested Objects

The subproperty of an objects can be accessed by chaining together the dot or brachet notation.

#### Example:
```
const ourStorage = {
  "desk": {
    "drawer": "stapler"
  },
  "cabinet": {
    "top drawer": { 
      "folder1": "a file",
      "folder2": "secrets"
    },
    "bottom drawer": "soda"
  }
};

ourStorage.cabinet["top drawer"].folder2; // output will be secrets
ourStorage.desk.drawer; // output will be stapler

```

### Accessing Nested Array

Nested Array is simmilar to nested object so you can access nested arrays by chained bracket notation.

#### Example

```
const ourPets = [
{
animalType: "cat",
names: ["Meowzer", "Kit-cat"]
},
{
animalType: "dog",
names: ["Frankie", "Spot"]
}];

ourPets[0].names[1] // output will be kit-cat
ourPets[1].names[0] // output will be Frankie

```

### Loopds

=
=
=

continue
### Nesting For Loops
Looping throught Multi Dimension Array Examples

```
const arr = [
  [1,2], [3,4], [5,6]
]
for (let i=0; i<arr.length; i++){ // iterate througth the whole array
for (let j=0; j<arr[i].lenght; j++){ // arr[i].length here we are iterating on the first sub array
console.log(arr[i][j])
}
}
```

### Do While Loop

`do...while` loop will ensure that the code inside the loop will run at least once.












