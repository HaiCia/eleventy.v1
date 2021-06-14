---
layout: layouts/blog.njk
tags: blog
title: Intro to JS Practicals
date: 2021-06-14T18:55:31.744Z
thumbnail: https://www.freeimages.com/pl/photo/hi-tech-1-1554527
rating: 6
---
```javascript
// Task 1
function percentageCalculator(number, percentage) {
  return number * (percentage / 100);
}

let results = percentageCalculator(200, 15)

console.log(results);

// Task 2

function drinkOrder(size, drink) {
  
  switch(drink) {
    case "cola":
      softDrinkLabel = "Cola";
      break;
    case "lemon":
      softDrinkLabel = "Lemonade";
      break;
    case "orange":
      softDrinkLabel = "Orangeade"
  }
  return `You have ordered a ${size} glass of ${softDrinkLabel}`;
}

console.log(drinkOrder("small", "cola"));

// Task 3

function calculator(num1, num2, operator) {
  switch(operator) {
    case "add":
      operation = num1 + num2;
      sign = "+";
      break;
    case "substract":
      operation = num1 - num2;
      sign = "-";
      break;
    case "multiply":
      operation = num1 * num2;
      sign = "*";
      break;
    case "divide":
      operation = num1 / num2;
      sign = "/";
      break;
  }
  return `${num1} ${sign} ${num2} = ${operation}`;
}

console.log(calculator(35, 5, "divide"));
```