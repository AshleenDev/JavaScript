# JavaScript

## Comments

There are two types of comments.

```javascript
// Single line comments

/* Multi-line 
comments */
```
## Variables

```javascript
// The value of the variable CANNOT be changed later.
const name = 'Ashleen'; 

// The value of the variable can be changed later.
let age = 32;
```

## Functions
```javascript
// Define a function with a parameter
function double(number) {
  console.log(number * 2);
}

// Call the function
double(4);

/**
 * Output : 8
 */
```

## Strings

### Length of a string

```javascript
let country = "France";
let countryLength = country.length;

console.log(countryLength);

/**
 * Output : 6
 */
```

### Convert a string to uppercase

```javascript
let firstName = 'Ashleen';
firstName = firstName.toUpperCase();

console.log(firstName);

/**
 * Output: ASHLEEN
 */
```

### Convert a string to lowercase

```javascript
let firstName = 'AShleEn';
firstName = firstName.toLowerCase();

console.log(firstName);

/**
 * Output: ashleen
 */
```

## Arrays

### Declare an array

```javascript
// Declare an array
let countries = ['France', 'Belgium', 'Italy', 'Spain', 'Switzerland'];
```

### Append an item to an array in JavaScript

```javascript
let countries = ['France', 'Belgium', 'Italy', 'Spain', 'Switzerland'];

// Append an item to the end of the array
countries.push('Germany');

// Append an item to the beginning of the array
countries.unshift('United Kingdom');
```
