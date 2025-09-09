### 1) What is the difference between var, let, and const?

<br><b>answer: </b><br>

#### var → Function-scoped, can be redeclared and updated, hoisted with undefined.
#### let → Block-scoped, can be updated but not redeclared in the same scope, hoisted but not initialized.
#### const → Block-scoped, cannot be updated or redeclared, must be initialized at declaration.

### 2) What is the difference between map(), forEach(), and filter()?

<br><b>answer: </b>

#### map() → Returns a new array after applying a function to each element.
#### forEach() → Iterates over elements but returns nothing (undefined).
#### filter() → Returns a new array containing elements that pass a given condition.

### 3) What are arrow functions in ES6?

<br><b>answer: </b>

#### Arrow functions are a new way to write functions introduced in ES6. They provide a shorter syntax compared to traditional function expressions.

### 4) How does destructuring assignment work in ES6?

<br><b>answer: </b>

#### Destructuring allows us to unpack values from arrays or properties from objects directly into variables.This avoids writing repetitive code and makes it easier to extract data. It is useful when working with arrays, objects, or function return values.

### 5) Explain template literals in ES6. How are they different from string concatenation?

<br><b>answer: </b>

#### Template Literals in ES6 are a new way to create strings using backticks (`). They support multi-line strings (no need for \n or concatenation). They also support embedded expressions using ${expression} for dynamic content. String interpolaration is also possible.

#### differences:
#### 1. Template literals, introduced in ES6, offer a modern and intuitive way to handle strings in JavaScript. Unlike traditional string concatenation — which relies on quotes and the + operator and often results in cluttered. Template literals use backticks and allow direct embedding of variables and expressions via ${}.
#### 2. They naturally support multi-line strings without needing escape characters or manual line breaks, making them ideal for composing messages, HTML snippets, or complex dynamic content.
#### 3. Overall, template literals improve readability, reduce errors, and enable more expressive and maintainable code compared to the older concatenation approach.