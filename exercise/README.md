# ![DOM Events Lab - Exercise](./assets/hero.png)

## Introduction

Before diving into the exercise, take a moment to inspect the provided starter code. You'll find that both the HTML and CSS portions have already been provided for you. Your primary focus will be on using JavaScript in the `app.js` file to bring the calculator to life. Pay special attention to the `index.html` file and any provided `attributes` that will help you interact with the calculator's elements. Before you start coding, open the `index.html` file in your browser to familiarize yourself with the user interface you'll be working with.

## User stories

User stories are crucial in breaking down the features of an application and structuring the development process. 
They are typically written as "As a user, I want to...", which helps in focusing on user needs and experiences.

Here are the user stories for this lab:

- As a user, I want to be able to select numbers so that I can perform operations with them.
- As a user, I want to be able to add two numbers together.
- As a user, I want to be able to subtract one number from another.
- As a user, I want to be able to multiply two numbers together.
- As a user, I want to be able to divide one number by another.
- As a user, I want to be able to see the output of the mathematical operation.
- As a user, I want to be able to clear all operations and start from 0.

> 🧠 Formatting your user stories as smaller and more focused can make the development process easier to manage.

## Implement a user story

Let's take the first one as an example and work through some preliminary questions and implementation steps together.

 - **User Story:** As a user, I want to be able to select numbers so that I can perform operations with them.

### Preliminary Questions

When planning our code, we might consider the following:

1. How do we capture the "value" when a number button is clicked?
2. What steps are needed to achieve this?
3. Can we use existing attributes to tie events to our number button elements?

### Implementation

After thinking through our approach, we could take the following steps to implement this user story:

1. Query for the number buttons

- Using `querySelectorAll` and the existing `number` class, we can store a cached element reference for our number buttons.

```javascript
const numbers = document.querySelectorAll(".number")
```

2. Add event listeners

- Using the `forEach` method, add event listeners to each number button. 

- We can use a `console.log` within the event listener to verify that the click event captures the correct value from the button. This step is for testing purposes and will be replaced with actual logic to capture and use the button's value later. 


```javascript
numbers.forEach(number => {
  number.addEventListener("click", (event) => {
    // This log is for testing purposes to verify we're getting the correct value
    console.log(event.target.innerText);
    // Future logic to capture the button's value goes here...
  });
});
```

> `event.target.innerText` attempts to access the inner text of the clicked element. This is typically the text content inside an HTML element.

When any element in the numbers collection is clicked, this code will log its inner text (the visible text inside the element) to the console.

Now that we are able to 'select' numbers by clicking on number buttons, our User Story is satisfied.

## Lab Exercise

Your primary goal is to implement the user stories listed above. The Minimum Viable Product (MVP) for this lab focuses on basic functionality and does not cover edge cases, such as pressing an operator button multiple times. You are encouraged to tackle these advanced cases once you have achieved the MVP.

## Tips for a smooth lab experience

1. **Start with the basics**: Begin by implementing simple operations like 1 + 1 or 4 - 2.

2. **Advance to more complex operations**: Once you're comfortable, try handling operations with multi-digit numbers, like 15 - 10 or 23 + 57.

3. **Understand button roles**: Remember, each calculator button serves a specific purpose. Differentiate between number buttons and operator buttons. Consider how the event handling might vary between them.

Happy coding! 🎉