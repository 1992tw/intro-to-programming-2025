# Callbacks

## Overview

No overview provided

## Learning Objectives

Learning objectives will be defined as the lesson progresses.

## Topics Covered

Topics will be covered as the lesson progresses.

## Status

pending

## Assignment

Assignment for Lesson 4

### Objective

No objective specified

### Expected Capabilities

Expected capabilities will be defined as the lesson progresses.

### Instructions

Instructions will be provided when the lesson is generated.

### Tasks

#### Task 1: Task 1

**NOTE: If the CodeSandbox file gets updated, the code example below may not be up to date.  You can confirm the most recent version of this assignment by clicking this:**
[Link to CodeSandbox Assignment](https://codesandbox.io/p/sandbox/lesson-4-javascript-array-methods-2025-w4mycz?file=%2Fsrc%2Findex.mjs)

``` javascript
//--------------- IMPORTANT!!! ---------------

// Use the keyboard shortcut Alt + Z (for PC) or Option + Z (for Mac) to allow word wrap on this document.  Word wrap breaks the lines so you don't have to keep scrolling left and right to read.

//READ THE INFORMATION IN THE BROWSER WINDOW PANEL ON THE RIGHT BEFORE BEGINNING YOUR ASSIGNMENT!!

//---------- OVERVIEW AND INSTRUCTIONS ----------

//----------------------------------
// LESSON 4 ARRAY METHODS
//----------------------------------

//  This is the coding assigment for the fourth week of the Intro to Programming course from Code the Dream. The concepts touched on in this assignment include:

//  - Using Array Methods
//  - Understanding about iterative methods
//  - Learning about callbacks
//  - Creating Higher Order Functions
//  - Using existing Array Higher Order Functions (e.g. forEach(), map(), filter(), etc.)

// In this assignment you will write your own code. Your instructions are listed as "comments", meaning the instructions are grayed out and start with '//' at the beginning of the line of code. Put your answers immediately below the instructions for each question. As mentioned in the Welcome to week 4 information to the right, you'll need to use console logs for all the questions to check your code output. Using a function in a console.log is very similar to how you were using them with variables last week. To invoke/call the function use the syntax:

//  console.log("Q#: ", functionName(anyInput))

// Please be sure to check the output of your called functions and console logs in the Console tab to the bottom right of this screen. If your Console is not showing, click the Inspect Button in the top right (see the Welcome to week 4 information to the right if you need help finding that)  Check to make sure that the output you get in your Console is the expected output.

// ----- Practice JS array methods: forEach -----
//---------- QUESTION 1 ----------
// Create an variable called 'names' and assign it an array of people's names.  Write a function called 'printNames' that uses the forEach array method to log each name in an array to the console.  Remember, since you're using the console.log in the function, you'll just want to call your function and pass it the array of names when testing your code.

// EXAMPLE CALL:
//    let names = ["Juan Marcos", "Aleksandra Ivanov", "Zhang Wei", "Bernice King"];
//    console.log("Q1 printNames:");
//    printNames(names);

// EXAMPLE OUTPUT:
//   Q1 printNames:
//   Juan Marcos
//   Aleksandra Ivanov
//   Zhang Wei
//   Bernice King

// PUT YOUR CODE HERE

//---------- QUESTION 2 ----------
// Create a variable called 'trees' and assign it an array of 3 objects.  Each object should have a 'type' property and a 'height' property.  You can use 'type' to describe the type of tree (ex. Dogwood, Maple, Oak, Elm, etc.) and give them any height.  Now write a function called 'logTreeType' that uses forEach to log the type of each tree object to the console.

// EXAMPLE CALL:
//   const trees = [
//     { type: "oak", height: "30m" },
//     { type: "elm", height: "25m" },
//     { type: "birch", height: "18m" } ]
//   console.log("Q2 logTreeType:");
//   logTreeType(trees);

// EXAMPLE OUTPUT:
//   Q2 logTreeType:
//   oak
//   elm
//   birch

// PUT YOUR CODE HERE

//---------- QUESTION 3 ----------
// Create a variable called 'myNumbers' and assign it an array of numbers.  Now write a function caled 'totalPoints' that uses forEach to add up all the numbers in that array of numbers.

// EXAMPLE CALL:
//   let myNumbers = [1, 2, 7, 5, 8];
//   console.log (`Q3 totalPoints [${myNumbers}]:`, totalPoints(myNumbers));

// EXAMPLE OUTPUT:
//   Q3 totalPoints [1,2,7,5,8]:  23

// Try a few different input arrays to verify your code is working.

// PUT YOUR CODE HERE

//---------- QUESTION 4 ----------
// Create a variable called 'myWords' and assign it an array of words.  Then write a function called 'buildSentence' that takes in an array of words and uses forEach to add the strings together. It should also add a space, " ", after each word.

// EXAMPLE CALL:
//    myWords = ["You","can","if","you","think","you","can","!"];
//    console.log (`Q4 buildSentence [${myWords}]: `, buildSentence(myWords));

// EXAMPLE OUTPUT:
//   Q4 buildSentence [You,can,if,you,think,you,can,!]:  You can if you think you can !

// Note: You should have a space after the ! too
// Try a few different input arrays to verify your code is working.

// PUT YOUR CODE HERE

//---------- QUESTION 5 ----------
// Create a variable called 'decimals' and assign it an array of decimal numbers.  Write a function called 'logPercentages' that takes an array of decimal numbers and uses forEach to log each one with the numbers formatted as percentages. That means:
//    Multiply by 100
//    Include the percent symbol (%) at the end of the string

// EXAMPLE CALL:
//   let decimals = [0.75, 0.91, 0.2, 1.34];
//   console.log("Q5 logPercentages:");
//   logPercentages(decimals);

// EXAMPLE OUTPUT:
// Q5 logPercentages:
//   75%
//   91%
//   20%
//   134%

// PUT YOUR CODE HERE

// ----- Practice JS Array Methods - map -----
// ---------- QUESTION 6 ----------
// Let's practice using the map array method.  Create a variable called 'startingNums' and assign it an array of numbers.  Then write a function called 'addThreeToAll' that uses map to add 3 to each number in an array of numbers.

// EXAMPLE CALL:
//   let startingNums = [4, 41, 832, 72, 89];
//   console.log (`Q6 addThreeToAll [${startingNums}]: `, addThreeToAll(startingNums));

// EXAMPLE OUTPUT:
//   Q6 addThreeToAll [4,41,832,72,89]:  [ 7, 44, 835, 75, 92 ]

// PUT YOUR CODE HERE

// ---------- QUESTION 7 ----------
// Create a variable called 'baseNums' and assign it an array of numbers.  Write a function called 'squareAll' that takes in an array of numbers, and uses map to return an array containing the squares of each of the numbers.  Remember, you can square a number by multiplying it by itself, or by using the exponent operator like so:
// let number = 4
// number * number // 16
// number ** 2 // 16
// Note that the caret operator ^ does NOT mean exponent in JavaScript

// EXAMPLE CALL:
//   let baseNums = [4, 41, 832, 72, 89];
//   console.log (`Q7 squareAll [${baseNums}]:`, squareAll(baseNums));

// EXAMPLE OUTPUT:
//   Q7 squareAll [4,41,832,72,89]: [ 16, 1681, 692224, 5184, 7921 ]

// PUT YOUR CODE HERE

// ---------- QUESTION 8 ----------
// Write a function called 'allGreetings' that takes an array of names (strings) by using your 'names' variable from question 1. Return an array of greetings (strings). The greetings should each be "Hello, [name], nice to meet you!".  You might find it helpful to use template strings.

// EXAMPLE CALL: (using the names array from question 1)
//   console.log (`Q8 allGreetings [${names}]:`, allGreetings(names));

// EXAMPLE OUTPUT:
// Q8 allGreetings [Juan Marcos,Aleksandra Ivanov,Zhang Wei,Bernice King]: [
//  'Hello, Juan Marcos, nice to meet you!',
//  'Hello, Aleksandra Ivanov, nice to meet you!',
//  'Hello, Zhang Wei, nice to meet you!',
//  'Hello, Bernice King, nice to meet you!'
// ]

// PUT YOUR CODE HERE

// ---------- QUESTION 9 ----------
// Create a variable called 'users' and assign it an array of objects.  See example on line 153 below.  Write a function called 'getUsernames' that takes in an array of user objects and uses map to return an array of just the usernames.

// EXAMPLE CALL:
//   let users = [
//   {
//     username: "juan.marcos",
//     isAdmin: false,
//   },
//   {
//     username: "aleksandra.ivanov",
//     isAdmin: false,
//   },
//   {
//     username: "zhang.wei",
//     isAdmin: false,
//   },
//   {
//     username: "bernice.king",
//     isAdmin: true,
//   }
//   ];
//
//  console.log (`Q9 getUsernames:`, getUsernames(users));

// EXAMPLE OUTPUT:
//   Q9 getUsernames: [ 'juan.marcos', 'aleksandra.ivanov', 'zhang.wei', 'bernice.king' ]

// PUT YOUR CODE HERE

// ---------- QUESTION 10 ----------
// Write a function called 'pluck' that takes in an array of objects and a string representing a key as parameters, and uses the map method to return an array of the values at that key for each of the objects.  For example, if we used the users array from the last exercise, we could do pluck(users, 'username') to get the same results as the last question.  If any of the objects does not have a value at that key, the array should have undefined in that slot.  Hint: Using the square bracket notation, you can access a property of an object using a variable.

// EXAMPLE CALL: (using the users array from Q9)
//   console.log (`Q10 pluck "isAdmin":`, pluck(users, "isAdmin"));

// EXAMPLE OUTPUT:
//   Q10 pluck "isAdmin": [ false, false, false, true ]

// Try testing with username too!

// PUT YOUR CODE HERE

// ----- Practice JS methods - filter -----
// ---------- QUESTION 11 ----------
// Write a function called 'evenNumbers' that takes an array as an argument and uses the filter method.  Return only the even numbers from the array of numbers.  Remember - you can find out if a number is even by using the % operator (modulus operator) like this:
//  number % 2 === 0   (gives a true boolean result, for even numbers)

// EXAMPLE CALL:
//   let numberArray = [4, 41, 832, 72, 89, 120, 431, 505, 70];
//   console.log (`Q11 evenNumbers [${numberArray}]:`, evenNumbers(numberArray));

// EXAMPLE OUTPUT:
//   Q11 evenNumbers [4,41,832,72,89,120,431,505,70]: [ 4, 832, 72, 120, 70 ]
//
// If there are no even numbers in the array you make and use, return an empty array.

// PUT YOUR CODE HERE

// ---------- QUESTION 12 ----------
// Write a function called 'greaterThan100' that takes in an array of numbers and uses the filter method.  Return any items in the array that are greater than 100.

// EXAMPLE CALL:
//   let numArray = [4,41,832,72,89,120,431,505,70];
//   console.log (`Q12 greaterThan100 [${numArray}]:`, greaterThan100(numArray));

// EXAMPLE OUTPUT:
//   Q12 greaterThan100 [4,41,832,72,89,120,431,505,70]: [ 832, 120, 431, 505 ]
//
// If there are no numbers greater than 100, return an empty array.

// PUT YOUR CODE HERE

// ---------- QUESTION 13 ----------
// Write a function called 'nonAdminUsers' that takes in an array of user objects.  The objects should have a username and isAdmin property each like they do in Question 9.  The function should use the filter method to return the users who are not admins.

// EXAMPLE CALL: (using users array from Q9)
//   console.log (`Q13 nonAdminUsers:`, nonAdminUsers(users));

// EXAMPLE OUTPUT:
//   Q13 nonAdminUsers: [
//     { username: 'juan.marcos', isAdmin: false },
//     { username: 'aleksandra.ivanov', isAdmin: false },
//     { username: 'zhang.wei', isAdmin: false }
//   ]

// PUT YOUR CODE HERE

// ---------- QUESTION 14 ----------
// Write a function called 'countAdminUsers' that uses filter and the length method on the result from filter.  The function should return the number of users that have 'isAdmin: true' as part of their object.
// EXAMPLE CALL: (using users array from Q9)
//   console.log (`Q14 countAdminUsers:`, countAdminUsers(users));

// EXAMPLE OUTPUT:
//   Q14 countAdminUsers: 1

// It should only count Bernice King since she is the only admin in that example.

// PUT YOUR CODE HERE

// ---------- QUESTION 15 ----------
// Write a function called 'shorterThanX' that takes two arguments: an array of strings and an integer.  Use the filter method to return all the strings in the array whose length is shorter than the integer provided as an argument.  If there's no strings in the array that are shorter than the number, return an empty array.

// EXAMPLE ARRAY:
// let strings = [
//   "Four score and seven years ago",
//   "our forefathers brought forth on this continent a new nation",
//   "conceived in liberty",
//   "and dedicated to the proposition that all men are created equal",
//   "Now we are engaged in a great civil war",
//   "testing whether that nation",
//   "or any so conceived and so dedicated",
//   "can long endure.",
// ];

// EXAMPLE CALL1:
//   console.log (`Q15 shorterThanX 20:`, shorterThanX(strings, 20));
// EXAMPLE OUTPUT1:
//   Q15 shorterThanX 20: [ 'can long endure.' ]

// EXAMPLE CALL2:
//   console.log (`Q15 shorterThanX 30:`, shorterThanX(strings, 30));
// EXAMPLE OUTPUT2:
//   Q15 shorterThanX 30: [
//    'conceived in liberty',
//    'testing whether that nation',
//    'can long endure.'
//  ]

// PUT YOUR CODE HERE

// ---------- QUESTION 16 ----------
// Write a function called 'onlyStrings' that takes an array that has different types of elements (numbers, booleans, strings, etc.) and uses the filter method to return an array of only the strings.

// EXAMPLE CALL:
//   let manyTypes = [4, "4", "four score", 80, {age: 80}, ["nations"], {type: "free"}, "states"];
//   console.log (`Q16 onlyStrings [${manyTypes}]:`, onlyStrings(manyTypes));

// EXAMPLE OUTPUT:
//   Q16 onlyStrings [4,4,four score,80,[object Object],nations,[object Object],states]: [ '4', 'four score', 'states' ]

// PUT YOUR CODE HERE

// ----- Practice JS methods - find -----
// ---------- QUESTION 17 ----------
// Write a function called 'firstOdd' that takes an array of numbers as an argument.  The function should use the find method to find the first odd number in an array.  Remember - you can find out if a number is odd using the % operator like so:
// number % 2 === 1  (gives a true boolean result, for odd numbers)
// If there are no odd numbers, return undefined.

// EXAMPLE CALL:
//   let array = [4,41,832,72,89,120,431,505,70]
//   console.log (`Q17 firstOdd [${array}]:`, firstOdd(array));

// EXAMPLE OUTPUT:
//   Q17 firstOdd [4,41,832,72,89,120,431,505,70]: 41

// PUT YOUR CODE HERE

// ---------- QUESTION 18 ----------
// Write a function called 'divisibleByTen' that takes an array of numbers as an argument.  The function should use the find method to return the first number that is a multiple of 10.  If there are no numbers divisible by 10, return undefined.

// EXAMPLE CALL:
//   let divArray = [4,41,832,72,89,120,431,505,70]
//   console.log (`Q18 divisibleByTen [${divArray}]:`, divisibleByTen(divArray));

// EXAMPLE OUTPUT:
//   Q18 divisibleByTen [4,41,832,72,89,120,431,505,70]: 120

// PUT YOUR CODE HERE

// ---------- QUESTION 19 ----------
// Write a function called 'divisibleByX' that takes two arguments: an array and an integer.  The function should use the find method to return the first number in the array that's divisible by the integer that was passed as an argument.  If there are no values that are divisible by the second argument, return undefined.

// EXAMPLE ARRAY:
//    let numbers = [4,41,832,72,89,120,431,70];

// EXAMPLE CALL 1:
//    Qconsole.log (`Q19 divisibleByX ([${divArray}], 10):`, divisibleByX(numbers, 10));
// EXAMPLE OUTPUT 1: (if using the example array above)
//    Q19 divisibleByX ([4,41,832,72,89,120,431,505,70], 10): 120

// EXAMPLE CALL 2:
//    console.log (`Q190 divisibleByX ([${divArray}]. 3):`, divisibleByX(numbers, 3));
// EXAMPLE OUTPUT 2: (if using the example array above)
//    Q19 divisibleByX ([4,41,832,72,89,120,431,505,70]. 3): 72

// EXAMPLE CALL 3:
//    console.log (`Q19 divisibleByX ([${divArray}], 2):`, divisibleByX(numbers, 2));
// EXAMPLE OUTPUT 3: (if using the example array above)
//    Q19 divisibleByX ([4,41,832,72,89,120,431,505,70], 2): 4

// PUT YOUR CODE HERE

// ---------- QUESTION 20 ----------
// Write a function called 'startsWithLetter' that takes two arguments: an array of strings and a letter.  The function should use the find method to return the first string in the array that starts with the letter provided as the argument.  If there's no string in the array that starts with that letter, return undefined. The function should leave lowercase and uppercase letters alone.
// STRETCH GOAL: Throw an error "Letter must be a string of length 1" if the second argument is not a string, or if its length is more than 1.

// EXAMPLE ARRAY:
// let jokeStrings =
//   ["Do you want to hear a joke?",
//    "It's about a three-legged dog",
//    "The dog walks into a bar",
//    "The dog says, ",
//    "\"I'm looking for the man who shot my paw\"",
//    "Get it?"]

// EXAMPLE CALL 1:
//    console.log (`Q20 startsWithLetter T:`, startsWithLetter(jokeStrings, "T"));
// EXAMPLE OUTPUT 1: (if using the example array above)
//    Q20 startsWithLetter T: The dog walks into a bar

// EXAMPLE CALL 2:
//    console.log (`Q20 startsWithLetter I:`, startsWithLetter(jokeStrings, "I"));
// EXAMPLE OUTPUT 2: (if using the example array above)
//    Q20 startsWithLetter I: It's about a three-legged dog

// EXAMPLE CALL 3:
//    console.log (`Q20 startsWithLetter i:`, startsWithLetter(jokeStrings, "i"));
// EXAMPLE OUTPUT 3: (if using the example array above)
//    Q20 startsWithLetter i: undefined

// STRETCH GOAL EXAMPLE CALL:
//    console.log (`Q20 startsWithLetter dog:`, startsWithLetter(jokeStrings, "dog"));
// STRETCH GOAL EXAMPLE OUTPUT:
//    Q20 startsWithLetter dog: Error: Letter must be a string of length 1

// PUT YOUR CODE HERE

```


```

```

### Submission Instructions

Please submit on time

### Checklist

Checklist will be provided when the lesson is generated.

### Check for Understanding

Understanding checks will be provided when the lesson is generated.

## Subsections

### Lesson 4

- [V2 Scrimba - JS Deep Dive - Objects & Maps](https://v2.scrimba.com/javascript-deep-dive-c0a/~01d)
- **NOTE: Watch only the rest of the videos in the playlist (the last 3 you were instructed to skip last week).**
  - **If you are getting an alert "Only available to subscribers" you will need to be sure your are logged in to Scrimba with the email address we have on file for you, and that you have redeemed the link to free access you were emailed.  Remember to start at the 9th part titled "How Maps can do what Objects can't" and go to the end of the Objects section**

- The section on "Intermediate/advanced array magic" that you could skip in last week's Odin Project Fundamentals part 5 is now included in the following section for you to check out this week:

> ### Intermediate/advanced array magic
>
> Besides being a quick and handy way to store data, arrays also have a set of functions for manipulating that data in very powerful ways. Once you begin to master these functions you will start to see ways to use them all over the place! There are really only a handful of these functions… but as you’ll soon see, the possibilities of what you can do with them are near endless.
>
> 1. Start out by watching [this video](https://www.youtube.com/watch?v=HB1ZC7czKRs) from Wes Bos. To follow along, use your local Javascript30 repository. If you don’t have the repo yet, clone it from [here](https://github.com/wesbos/JavaScript30).
> 2. Watch and code with [Part 2](https://www.youtube.com/watch?v=QNmRfyNg1lw) of Wes Bos’s array series.
> 3. For a more comprehensive and in-depth guide to array methods in JavaScript, you can also check out this [array method guide](https://javascript.info/array-methods). This resource covers each method in detail, with examples and explanations of their usage.

# Callbacks

Callbacks are functions that you provide to another function or system to be executed when a certain condition or event occurs. They are a way of saying, "Hey, when this thing happens, do this specific task.”

Imagine you have a button on a website, and you want something to happen when the button is clicked. You could create a callback function that specifies what should happen when the button is clicked. This callback function is then associated with the button.

```jsx
// A function that adds two numbers and uses a callback to return the result
function addNumbers(a, b, callback) {
  const result = a + b;
  callback(result);
}

// Define a callback function to handle the result
function handleResult(result) {
  console.log("The result is: " + result);
}

// Call the addNumbers function with a callback
addNumbers(5, 3, handleResult);
```

In this example, the **`addNumbers`** function takes two numbers **`a`** and **`b`**, adds them together, and then calls a provided **`callback`** function with the result. The **`handleResult`** function is the callback, and it prints the result to the console.

This demonstrates how callbacks can be used to pass control from one function to another, allowing you to specify what should happen after a specific operation (in this case, addition) is complete.

Watch this video on the mistake with functions every developer makes, because remember **making mistakes is a great way to learn!** [YouTube Video Link](https://www.youtube.com/watch?v=7UMuJMiNjSk&t=98s)

Callbacks are a versatile and powerful concept in programming, and they can be used in various scenarios. Here are some common situations where callbacks are useful:

1. **Asynchronous Operations:** Callbacks are often used with asynchronous operations, like making network requests, reading files, or interacting with databases. They allow you to specify what should happen when the operation is completed without blocking the rest of your program.
2. **Event Handling:** In user interfaces, callbacks are used to respond to user interactions such as button clicks, mouse movements, or keyboard input. You define a callback function that gets triggered when the event occurs.
3. **Modular and Reusable Code:** Callbacks make it easier to write modular and reusable code. You can create functions that accept callbacks to perform specific tasks, allowing you to reuse those functions with different behaviors depending on the callback provided.
4. **Iterations and Loops:** Callbacks can be used in iterations and loops to execute a function for each element in a collection, like an array or a list. This is known as "callback-based iteration."
5. **Promises and Promisified Code:** In JavaScript, promises often work with callbacks to handle asynchronous tasks more cleanly. Promises provide a structured way to handle callbacks and make asynchronous code easier to read and maintain.

Overall, callbacks are a fundamental building block in software development, enabling you to define what should happen when a particular event or operation occurs, making your code more flexible, modular, and responsive.

We will be covering all these aspects of the uses of callbacks in later lessons, but it is important to understand how they work at a very basic level.

# Higher Order Functions

As we talked about callbacks previously, higher-order functions are those functions that receive a callback as a parameter.

```jsx
function addNumbers(a, b, callback) {
  const result = a + b;
  callback(result);
}
```

You can create your own higher-order functions or you can use many of the built-in higher-order methods that are part of the Array object.

Arrays have many methods and one category of methods it has are iterative which means they will iterate through the array and execute the callback function you pass to it for every element in the array.

Examples would be the [forEach()](https://javascript.info/array-methods#iterate-foreach), [map()](https://javascript.info/array-methods#map), [filter()](https://javascript.info/array-methods#filter), and others.

### The forEach() method

The forEach() method accepts a function as an argument. The function that you pass to the method is referred to as a **callback** function. 

You provide forEach() with a callback function. Then, internally, forEach() executes that callback function once for each element of the array. 

```jsx
const numbers = [1, 2, 3, 4];
numbers.forEach(function(num) {
  console.log(num);
});
// This will print each number in the array.
```

### The map() method

The map() will run the callback function for each of the items in the array. The map() method uses the callback function to create the items for a new array. The map() method will return a new array of the same number of elements as the original array and the forEach method will not return anything.

```jsx
const numbers = [1, 2, 3, 4];
const squared = numbers.map(function(num) {
  return num * num;
});
// squared is now [1, 4, 9, 16]
```

### The filter() method

Sometimes, you'll want to build up a new list of items that meet a particular condition. This method builds a new array of only the items that match a certain condition. The filter() method will “filter” the array so that you have only some of the items.

```jsx
const numbers = [1, 2, 3, 4, 5, 6];
const evenNumbers = numbers.filter(function(num) {
  return num % 2 === 0;
});
// evenNumbers is now [2, 4, 6]
```

**Note:**  There are many more of these type of methods, but do not worry about knowing how to use all of them, starting with a few is good enough.


**Video URL:** No video available

**Code Examples:**

No code examples available

**External Links:**

No external links available

**Quizzes:**

No quizzes available

## Supplemental Videos

No supplemental videos available

## References

No references available

## Podcast URL

No podcast available