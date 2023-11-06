# ![DOM Events Lab - Exercise](./assets/hero.png)

## Introduction
Before diving into the exercise, take a moment to inspect the provided starter code. You'll find that both the HTML and CSS portions have already been provided for you. Your task is to use DOM Manipulation in the `app.js` file to make the calculator functional. In the `index.html` file, take note of the attributes that allow you to access and interact with specific elements. Open up the `index.html` file in your browser to get a better sense of the interface you'll be working with. 

## User Stories
User stories are a great way to break down what the different features of the website are, and how to structure them. They are generally written out in the following way: "As a user, I want to...". 

> 🧠 Formatting your user stories as smaller and more focused can make the development process easier to manage.

Here is an example user story from this lab:

- As a user, I want to be able to select numbers so that I can perform operations with them.

Let's get some practice in how we might implement this user story. 

### Preliminary Questions
When approaching this task, we might consider the following:

1. When a user clicks on a button, our aim is to capture its unique "value".
2. What steps might we take to achieve this?
3. Are there any existing attributes useful for tying events to our number button elements?

### Implementation
After working out our approach, we could take the following steps to implement our user story:

1. First we create variables to store the values of selected numbers.
    ```javascript
    let firstValue = null;
    let secondValue = null;
    ```
2. Using `querySelectorAll` and the existing `number` class, we store a cached element references for our number buttons.
    ```javascript
    const numbers = document.querySelectorAll(".number")
    ```
3. Using the `forEach` method, we dynamically add an event listener to each number button.
    ```javascript
    numbers.forEach(number => {
      number.addEventListener("click", (event) => {
        // logic to capture the button's value...
      })
    })
    ```

## Lab Exercise
Your goal is to implement the user stories below. The Minimum Viable Product (MVP) build for this lab does not include consideration for edge cases. For instance, the scenario where a user presses an operator twice is beyond our MVP scope. However, addressing such cases could be a worthwhile challenge after meeting the MVP.

- As a user, I want to be able to select numbers so that I can perform operations with them.
- As a user, I want to be able to add two numbers together.
- As a user, I want to be able to subtract one number from another.
- As a user, I want to be able to multiply two numbers together.
- As a user, I want to be able to divide one number by another.
- As a user, I want to be able to see the output of the mathematical operation.
- As a user, I want to be able to clear all operations and start from 0.

## Tips
1. **Start with the basics**: Begin with simple operations involving single digits, e.g., 1 + 1 or 4 - 2.

2. **Move on to more complex values**: Once comfortable, move on to operations with multi-digit numbers, like 15 - 10 or 23 + 57.

3. **Button roles**: Remember, each calculator button serves a specific purpose. Differentiate between number buttons and operator buttons. Consider how the event handling might vary between them.