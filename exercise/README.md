# ![DOM Events Lab - Lab Exercise](./assets/hero.png)

## Introduction

Before diving into the exercise, take a moment to inspect the provided starter code. It contains essential building blocks for your calculator. Open up the `index.html` file in your browser to get a better sense of the interface you'll be working with. The complete HTML and CSS portions have been provided for you. Your main task is to use DOM Manipulation in `app.js` file to make the calculator functional.

## User Stories
User stories are a great way to break down what the different features of the website are, and how to structure them. They are generally written out in the following way: "As a user, I want to...". 

> 🧠 Formatting your user stories as smaller and more focused can make the development process easier to manage.

Here is an example user story from this lab:

- As a user, I want to be able to select numbers so that I can perform operations with them.

Let's get some practice in how we might implement this user story. 

When approaching this task, we might consider the following:

1. When a user clicks on a button, our aim is to capture its unique "value".
2. What steps might we take to achieve this?
3. Are there any existing attributes useful for tying events to our number button elements?

After working out our approach, we could take the following steps to implement our story:

1. Create variables like `firstValue` and `secondValue` to store the values of selected numbers.
2. Store a cached element references for the number buttons. Utilizing the existing `number` class might be helpful here.
3. Use the `forEach` method to dynamically add an event listener to each number button.

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
- At the start, concentrate on operations like adding or subtracting single digits (1+1).
- As you progress, start to work out an approach to dealing adding and subtracting multiple digits (15-10).
- Each button on the calculator has a distinct role. Think about the different considerations you might make for an event triggered by a number in contrast to an event triggered by an operator button.