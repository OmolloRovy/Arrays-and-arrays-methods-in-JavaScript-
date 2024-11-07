# Arrays and Array Methods in JavaScript

# Understanding Arrays
In JavaScript, an array is a collection of items, stored in a single variable. It's a fundamental data structure used to store and manipulate data efficiently. Arrays are declared using square brackets [] and elements are separated by commas.

### JavaScript
let fruits = ["apple", "banana", "orange"];


# Accessing Array Elements
To access a specific element, you use its index. Remember, indexing starts from 0.

### JavaScript
let firstFruit = fruits[0]; // "apple"
let lastFruit = fruits[fruits.length - 1]; // "orange"


# Common Array Methods
JavaScript provides a variety of built-in methods to manipulate arrays:

# Adding Elements
## push()
Adds one or more elements to the end of the array.
### JavaScript
fruits.push("grape"); // ["apple", "banana", "orange", "grape"]


## unshift()
Adds one or more elements to the beginning of the array.
### JavaScript
fruits.unshift("kiwi"); // ["kiwi", "apple", "banana", "orange", "grape"]

# Removing Elements
## pop()
Removes and returns the last element from the array.
### JavaScript
let removedFruit = fruits.pop(); // "grape"


## shift()
Removes and returns the first element from the array.
### JavaScript
let firstFruit = fruits.shift(); // "kiwi"


# Modifying Elements
## splice()
Removes or replaces elements at a specific index.
### JavaScript
fruits.splice(1, 1, "pear"); // ["kiwi", "pear", "orange"]


# Searching and Sorting
## indexOf()
Returns the index of the first occurrence of an element.
### JavaScript
let index = fruits.indexOf("orange"); // 2

# lastIndexOf()
Returns the index of the last occurrence of an element.
## JavaScript
let lastIndex = fruits.lastIndexOf("orange"); // 2

## sort()
Sorts the array elements.
### JavaScript
fruits.sort(); // ["kiwi", "orange", "pear"]


## reverse()
Reverses the order of elements in the array.
### JavaScript
fruits.reverse(); // ["pear", "orange", "kiwi"]


# Iterating Over Arrays
## for loop:
### JavaScript
for (let i = 0; i < fruits.length; i++) {
    console.log(fruits[i]);
}


## forEach()
### JavaScript
fruits.forEach(function(fruit) {
    console.log(fruit);
});


# Other Useful Methods
## join()
Joins all elements of an array into a string.
## slice()
Extracts a section of an array.
## concat() Merges two or more arrays.
## filter() 
Creates a new array with elements that pass a test.
## map() Creates a new array by transforming each element.
## reduce() 
Reduces an array to a single value.
