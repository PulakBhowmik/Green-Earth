## WELCOME TO ( সহজ সরল সিম্পল ) ASSIGNMENT-006

### 📅 Deadline For 60 marks: 9th September, 2025 (11:59 pm ⏱️)

### 📅 Deadline For 50 marks : 13th September , 2025 (6:00 pm⏱️)

### 📅 Deadline For 30 marks: Any time after 13the September , 2025 (6:01 pm⏱️).

---
# Green Earth


## Private Repository: https://classroom.github.com/a/nVZrg5R9 

## Alternative Private Repository: https://classroom.github.com/a/KCGI14ST 

## Alternative Private Repository: https://classroom.github.com/a/JMuIYqgK 


---
🌴 API Endpoints
---
1. Get 🌴All Plants
```bash
https://openapi.programming-hero.com/api/plants
```

2. Get 🌴All categories <br/>
```bash
https://openapi.programming-hero.com/api/categories
```


3. Get 🌴plants by categories <br/>
```bash
https://openapi.programming-hero.com/api/category/${id}
```

```bash
https://openapi.programming-hero.com/api/category/1
```

4. Get 🌴Plants Detail <br/>

```bash
https://openapi.programming-hero.com/api/plant/${id}
```

```bash
https://openapi.programming-hero.com/api/plant/1
```
---




## ✅ Main Requirements 

#### 1) Navbar

- Website **logo/name** on the **left**  
- **Menu items** in the **center** 
- **Plant a Tree button** on the **right** 

#### 2) Banner 
- A **background image**  
- A **title** and **subtitle**  
- A **centered button**  

#### 3) About Campaign
- **Section heading**  
- **Image on the left**, **text on the right**  

#### 4) Our Impact Section 
- Show **3 cards** with campaign **statistics**  

#### 5) Plant a Tree Today Section & Footer
- **Form**: Name, Email, Number of Trees  
- **Footer** with copyright info 

#### 6) Responsiveness 
- Website must be **mobile responsive**  

---
#### 7) Create a README file to answer the following question-


#### 1) What is the difference between var, let, and const?

#### 2) What is the difference between map(), forEach(), and filter()? 

#### 3) What are arrow functions in ES6?

#### 4) How does destructuring assignment work in ES6?

#### 5) Explain template literals in ES6. How are they different from string concatenation?

## ⚙️ Functionalities 

1) Category Loading 
Load Tree Categories dynamically on the left side.

2) Category Click → Tree Data 
On clicking a category: load trees of that category.

Display in a 3-column card layout.

3) Card Contents 
 Each card includes:

        - Image

        -  Name

        - Short description

        - Category

        - Price

        - Add to Cart button

4) Modal on Card Click 
Clicking a tree name on a card opens a modal with full tree details.


##  🧪 Challenges 


    1) Add to Cart 
    Clicking Add to Cart: - Adds the tree to Cart List
                          - Shows tree name 

    2) Total Calculation 
    Calculate total price of trees in cart.

    3) Remove from Cart 
    Clicking ❌ removes tree and deducts price from total.

    4) Loading Spinner
    Show spinner while data is loading.

    5) Active Button State 
    Highlight active category button when selected.



🧰 Technology Stack:
        
        HTML

        CSS (Vanilla / Tailwind / DaisyUI)

        JavaScript (Vanilla only, no frameworks)

📌 Rules
✅ At least 5 meaningful commits

❌ No dummy text or Lorem Ipsum — must use relevant content





## 🔗 Submission
- **Live Link :** YOUR_DEPLOYED_URL_HERE  
- **GitHub Private Repository:** YOUR_REPO_URL_HERE  



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