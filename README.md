# Week 4 – FNB App Academy

Welcome to **Week 4** of the FNB App Academy! This week marks the beginning of the **Intermediate Level**, where we step beyond static websites and start adding real functionality using **JavaScript**.

After building complete apps using HTML and CSS in the beginner level, we now introduce the third and final language in the HTML5 family – **JavaScript**. JavaScript lets us add interactivity, perform calculations, and make decisions based on user input.

---

## 🚀 What’s New This Week?

- Introduction to JavaScript and its role in web development
- Writing basic JavaScript code and displaying output
- Creating and using variables
- Using conditionals for decision-making
- Writing and calling functions
- Working with function parameters and return values
- Understanding variable scope
- Building a login form mini project
- Learning the switch statement
- Handling numbers and strings properly

---

## 📚 Lessons Covered

### Lesson 1: JavaScript Outputs
- Using JavaScript to display text and numbers on a webpage

### Lesson 2: Variables Part 1
- Declaring and assigning string values to variables

### Lesson 3: Variables Part 2
- Using variables to store and calculate numeric values

### Lesson 4: Conditionals
- Using `if...else` statements to perform logic-based actions

### Lesson 5: Functions (Intro)
- Using built-in functions like `onclick` to trigger events

### Lesson 6: Functions Continued
- Creating custom functions and combining them with conditionals

### Lesson 7: Function Parameters
- Feeding data into a function using parameters

### Lesson 8: Function Return
- Returning processed data from a function for later use

### Lesson 9: Variable Scope
- Understanding where variables are accessible in your code

### Lesson 10: Mini Project – Login Form Part 1
- Creating a login form using HTML and preparing JavaScript validation

### Lesson 11: Mini Project – Login Form Part 2
- Validating login credentials using JavaScript functions and conditionals

### Lesson 12: The SWITCH Statement
- Using the `switch` statement to handle multiple conditions

### Lesson 13–15: Numbers and Strings
- Converting strings to numbers and avoiding type conversion errors

---

## 💻 Example Code Snippet

```javascript
function verifyUser(){
  var username = document.getElementById("usernameInput").value;
  var password = document.getElementById("passwordInput").value;
  if(username === "Bond" && password === "007"){
    document.getElementById("message").innerHTML = "Correct. Logging you in...";
  } else {
    document.getElementById("message").innerHTML = "Username or password are incorrect.";
  }
}
