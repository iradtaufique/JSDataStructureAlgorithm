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

### undefined returned by a function

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


### Javascrispt Objects

objects are similar to array except that instead of using indexes to access and modifies data, object use `Properties`.

#### Example:

```
const cat = {
  "name": "Whiskers",
  legs: 4,
  tails: 1,
  "enemies": ["Water", "Dogs"]
};
```

you can omit double or single quotes on property name in case it is single-word-string-propery-name like `legs or tails`as it is on example above.

### Access Object Properties with (.) Dot notation and ([]) bracket notation

#### Object Example No1

```
const myObj = {
  prop1: "val1,
  prop2: "val2"
  }
  
  // accessing prop1 value
  const prop1val = myOb.prop1 // Using dot notaion
  const prop2val = myObj["prop2"] // Using Bracket notation
 ``` 
### Updating Object Property

By using the Previous Example Example No1 we can update prop1 value

#### Example: 
```
myObj.prop1 = "val 1 updated" // using dot notation
myObj["prop1"] = "val 1 updated" // using sqaure brachets

```

### Adding New Property to an objects

The some way we have updated or modified an object is the some way we have to add new propery on an object.


if property name exist: `update the value`.

if propety name does not exist: `add new property to on object`.


### Delete Property from Javascript object

```
delete objectname.properyname;
```

### Testing objects for Property

`.hasOwnProperty(propertyname)` is a javascript method that is used to check if the object has cetain property name or not. `hasOwnProperty` return `true` when object has that property name ahterwise return `false`.

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

This is an array which contains one object inside. The object has various pieces of metadata about an album. It also has a nested `formats` array. If you want to add more album records, you can do this by adding records to the top level array. Objects hold data in a property, which has a key-value format. In the example above, `"artist": "Daft Punk"` is a property that has a key of `artist` and a value of `Daft Punk`.

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












