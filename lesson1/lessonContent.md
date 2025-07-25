# ## Scrimba

## Overview

No overview provided

## Learning Objectives

Learning objectives will be defined as the lesson progresses.

## Topics Covered

Topics will be covered as the lesson progresses.

## Status

pending

## Assignment

Assignment for Lesson 1

### Objective

No objective specified

### Expected Capabilities

Expected capabilities will be defined as the lesson progresses.

### Instructions

Instructions will be provided when the lesson is generated.

### Tasks

#### Task 1: Task 1

**NOTE: If the CodeSandbox file gets updated, the code example below may not be up to date.  You can confirm the most recent version of this assignment by clicking this:**
[Link to CodeSandbox Assignment](https://codesandbox.io/p/sandbox/lesson-1-javascript-basics-and-functions-2025-nrfx4t?file=%2Fsrc%2Findex.mjs)

``` javascript
//--------------- IMPORTANT!!! ---------------

// Use the keyboard shortcut Alt + Z (for PC) or Option + Z (for Mac) to allow word wrap on this document.  Word wrap breaks the lines so you don't have to keep scrolling left and right to read.

//READ THE INFORMATION IN THE BROWSER WINDOW PANEL ON THE RIGHT BEFORE BEGINNING YOUR ASSIGNMENT!!

//---------- OVERVIEW AND INSTRUCTIONS ----------

//----------------------------------
// LESSON 1 BASICS AND FUNCTIONS
//----------------------------------

// This is the coding assigment for the first week of the Intro to Programming course from
// Code the Dream. The concepts touched on in this assignment include:
//   - The basic syntax of the JavaScript programming language
//   - Basic programming concepts like variables, data types, and conditional statements
//   - Troubleshooting programming problems
//   - Encapsulating code with Functions
//   - Passing Information Into Functions

// In this assignment you will write your own code. Your instructions are listed as "comments", meaning the instructions are grayed out and start with '//' at the beginning of the line of code. Put your answers immediately below the instructions for each question. As mentioned in the Welcome to Class info in the browser on the right, the first few questions have console logs provided. They are currently commented out so they will not show errors in your console.  Please remove the '//' from the left of the console log to "comment them in" making them active code.  Add console logs for all the remaining questions to check your code output. There are sample console logs for all questions, but be sure to use some of your own values and function inputs as well.

// To use a function in a console.log you invoke/call the function as part of the console log like this:
//  console.log("Q#: ", functionName(anyInput))

// Please be sure to check the output of your called functions and console logs in the Console tab to the bottom right of this screen. If your Console is not showing, click the Inspect Button in the top right (see the Welcome to class information to the right if you need help finding that)  Check to make sure that the output you get in your Console is the expected output.

// *********
// NOTE: THE CONSOLE WILL UPDATE AS YOU TYPE!  LOOK AT THE MOST RECENT OUTPUT TO MAKE SURE YOUR CONSOLE LOGS ARE DISPLAYING WHAT YOU EXPECT!!
// *********

// ---------- QUESTION 1 ----------
// Declaring and giving string values to variables.
// Create three variables.  First let's make sure we're using "camel case" where all letters are lowercase except for the first letter of words that are in the middle.  This is the accepted standard for Javascript code.  Your first variable should be titled "firstName" with the value of your first name as a string.  Your second variable should be titled "lastName" with the value of your last name as a string.  The last variable should be titled "country" with the value of the name of the country where you were born as a string.

//PUT YOUR CODE HERE

// console.log("Q1: My first name is: ", firstName);
// console.log("Q1: My last name is: ", lastName);
// console.log("Q1: I was born in the country: ", country);

// ---------- QUESTION 2 ----------
// Declaring and giving numerical values to variables.
// Create four variables.  One titled "floatingPoint" with the value of any floating point number you choose.  One titled "integer" with the value of any integer number you choose.  One titled "negative" with the value of any negative number you choose.  One titled "notANumber" with the value of 4 multipled by a string of your choice.
//NOTE: Remember from your lessons that JavaScript can treat large numbers differently than you might expect.

//STRETCH GOAL: You'll see "Stretch Goal"s throughout the course. Stretch Goals are optional, but are encouraged as they help you try your hand at something a little more advanced for the week/assignment/question. Create a fifth variable titled "bigNumber" that is 16 or more numbers long. Then write your console.log and see what happens as you play and practice working with large numbers.

// PUT YOUR CODE HERE

// console.log(
//   "This is a decimal, also called a floating point number: ",
//   floatingPoint
// );
// console.log("Q2: This is a whole number, also called an integer: ", integer);
// console.log("Q2: This is a negative number: ", negative);
// console.log("Q2: You can't mulitply 4 by a word! ", notANumber);

// ---------- Question 3 ----------
// Declaring and giving boolean values to variables.
// Create two variables.  Name the first variable anything you want and give it the value of true.  Name the second variable a different name than the first and give it the value of false.

// PUT YOUR CODE HERE

// console.log("The variable I made true is: ");
//The output of the above should be true.
// console.log("The variable I made false is: ");
//The output of the above should be false.

// ---------- QUESTION 4 ----------
// String Concatenation
// Create a variable that makes a concatenated string out of the variables you made in Question 1. Be sure you're using your Q1 variables and not making new ones.
// Suggested text: Hello! My name is (your first name variable and last name variable concatenated here) and I was born in (your country variable here)
// You can also choose to make the text between the variables strings and concatenate all of them together.

// STRETCH GOAL: For this stretch goal, make a second variable that still concatenates your variable from Q1, but uses template literals.

// PUT YOUR CODE HERE

// Don't forget your console.logs!

// ---------- QUESTION 5 ----------
// Make two variables.  One will hold the addition of your your floating point and integer variables from Q2, the other should hold the addition of your integer and negative number from Q2.

// PUT YOUR CODE HERE

// Don't forget your console.logs!

// ---------- QUESTION 6 ----------
// String Methods
// Create four variables named "length", "firstInitial", "lastInitial", and "capitalize".  Using string methods, assign the length of your first name (use your variable from Q1) to the "length" variable. Assign the first letter of your first name (use your variable from Q1) to the "firstInitial" variable.  Assign the LAST letter of your first name (use your variable from Q1) to the "lastInitial" variable.  Change your first name to all capital letters and assign it to the "capitalize" variable.

//STRETCH GOAL: Create a variable called "weirdInitials". Using string methods, have weirdInitials result in the value of the LAST letters of any first and last names and should be capitalized.  Example: "Sally Smith"'s weird initials should be "YH" and "Jose Rodriguez"'s inititals should be "EZ"

// PUT YOUR CODE HERE

// Don't forget your console.logs!

// ---------- QUESTION 7 ----------
// Declare a variable named "answer7".  Then create a conditional if else statement that will assign the value of true to the answer7 variable if your integer from Q2 is greater than 10 and assign it false if it is not.

// STRETCH GOAL: Make an if / else if / else statement that assigns answer7 the value of "less than" if your integer from Q2 is less than 10, "equal to" if it's equal, and "greater than" if it's greater.

// PUT YOUR CODE HERE

// Don't forget your console.logs!

// ---------- QUESTION 8 ----------
// Declare a variable called "age" and assign it that value of your age in years.  Create a conditional statement that will console.log the phrase "Age is just a number!" if your age is less than or equal to 30 and "Young at heart!" if your age is greater than 30.

//STRETCH GOAL: Combine your skills!  Use template literals to console.log your name in the phrase as in "Sally, age is just a number!" or "Jose, you're young at heart!"

// PUT YOUR CODE HERE

// Don't forget your console.logs!

// ---------- QUESTION 9 ----------
// Create a variable "randomNum" to be a random number generator that randomly returns either the number 1, 2, or 3 (you can use this resource to help you solve how to do this part: https://www.w3schools.com/js/js_random.asp). Now let's make a "Magic 8 Ball" using if elseif else that returns a different phrase for each of the three possible numbers.
// If your random number is 1, console.log the phrase "It is certain.".
// If it is 2, console.log "Perhaps.".
// If it is 3, console.log "Absolutely not.".

// STRETCH GOAL: Complete Q9 using a switch statement instead of if elseif else.

// PUT YOUR CODE HERE

// Don't forget your console.logs!

// ---------- QUESTION 10 ----------
// Declare a variable named "exampleNum".  Give it the value of a floating point number with 4 decimal places.  Using a Number method round it to the nearest two decimal place. Example if the number is 21.4572, exampleNum should become 21.46.

// STRETCH GOAL: Achieve the same results as Q10 using Math methods instead of Number methods. HINT: you may need to alter the variable over a series of calculations/method uses.

// PUT YOUR CODE HERE

// Don't forget your console.logs!

// ---------- QUESTION 11 ----------
// Declare two variables named "stringNum" and "mathNum".  Assign stringNum a STRING of numbers and mathNUM numbers.  Create a third variable named "answer11" and have it multiply stringNum and mathNum.  Remember to convert your string in order for it to properly calculate!

// PUT YOUR CODE HERE

// Don't forget your console.logs!

// ---------- QUESTION 12 ----------
//Create a function titled 'messageString'.  Inside the function,  declare a variable named 'message' and assign it the string "Welcome to Code the Dream".  Return the 'message' variable.

// EXAMPLE LOG:
//    console.log("Q12: ", messageString());
// EXAMPLE OUTPUT:
//    Q12: Welcome to Code the Dream!

//PUT YOUR CODE HERE

// ---------- QUESTION 13 ----------
// Create a function called 'combineStrings'.  Inside the function, declare two variables named 'string1' and 'string2'.  Assign them the strings 'Good' and 'Evening' respecitvely.  Return the two strings concatenated with a space in between.

// EXAMPLE LOG:
//    console.log("Q13: ", combineStrings());
// EXAMPLE OUTPUT:
//    Q13: Good Evening

//PUT YOUR CODE HERE

// ---------- QUESTION 14 ----------
// Let's start working with parameters.  Create a function called 'useParams' that takes one parameter and returns that parameter with the all letters capitalized.

// EXAMPLE LOG:
//    console.log("Q14: ", useParams("hello"));
// EXAMPLE OUTPUT:
//    Q14 HELLO

//PUT YOUR CODE HERE

// ---------- QUESTION 15 ----------
// Now let's work with strings... Create two variables named 'word1' and 'word2' and assign them any strings you want.  Then create a function called 'biggestStringLength' that takes word1 and word2 as parameters and returns the length of the longer string. If they are of equal length, just return that length.  Stretch your skills by making an empty string and seeing what happens in that situation.

// EXAMPLE LOG:
//    console.log("Q15: ", biggestStringLength(word1, word2));
// EXAMPLE OUTPUT: (if your word1 was 'Code' and word2 was 'Dream')
//    Q15: 5

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

### Lesson 1 BIG BIG TIME

Students have access to **[V2 Scrimba - Courses](https://v2.scrimba.com/courses)** and all of their courses _(be sure you have used the link emailed to you to gain access; you will need to login to Scrimba with the email account you provided to us as the way to contact you)_. Scrimba is an interactive learning platform where students can interact with the video content code editor.  

### Scrimba

The interface probably will look a little different than other video-based learning tools (e.g. Treehouse, Udemy, Khan Academy, etc.). Once logged in you can access the course library from the **Courses** link in the menu. 

![V2 Course Menu](https://github.com/Code-the-Dream-School/intro-to-programming-2024/blob/0431b040aa24c477fb906fe1842119219790a7af/v2Scrimba%20Course%20Menu.png?raw=true)

The Scrimba Courses Library page will show all courses and you can filter by Topic and choose the course you want to look at. Each week, there will be links to specific course lesson material that will cover the topics for that week.

![V2 Scrimba Courses Library](https://github.com/Code-the-Dream-School/intro-to-programming-2024/blob/42d3c9f76a9f807f7e8f10ab508a883a0d080437/v2Scrimba%20Courses.png?raw=true)


### Scrimba Lesson Interface

In order to see a particular course’s lesson content you have to first “enroll” in the course. This involves clicking a start button.

![V2 Start Course](https://github.com/Code-the-Dream-School/intro-to-programming-2024/blob/8b10eb42b737412ad320d91c40cafe41bc8699a9/v2Scrimba%20Start%20Course.png?raw=true)

Afterward, a course menu will allow you to navigate to each lesson

![V2 Course Menu](https://github.com/Code-the-Dream-School/intro-to-programming-2024/blob/249e6d0521e5536abe9160f0a7c8d54033113035/v2Scrimba%20Individual%20Course%20Menu.png?raw=true)

You click the name of the section you're on in the bottom left to go back to the course menu.

![V2 Return to Course Menu](https://github.com/Code-the-Dream-School/intro-to-programming-2024/blob/249e6d0521e5536abe9160f0a7c8d54033113035/v2Scrimba%20get%20back%20to%20menu.png?raw=true)


## You can _either_ use the written Odin Project lessons _or_ the video lessons in Scrimba. You can do both if you have them time and want to, but using just one or the other will teach what is needed to complete the coding assignments.
For the Odin Project, Go to each link in this list and read through the content on that page. If there are links you are redirected to as you read/work through the content, follow those links as well and read the content there too.

### Odin Project
- [Problem-Solving](https://github.com/Code-the-Dream-School/intro-to-programming-2025/wiki/Problem-Solving)
- [The Odin Project – Fundamentals Part 1](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/fundamentals-part-1)
- [The Odin Project – Fundamentals Part 2](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/fundamentals-part-2)
- [The Odin Project – Fundamentals Part 3](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/fundamentals-part-3)

### Scrimba
- [V2 Scrimba - JS Deep Dive - Variables and Strings](https://v2.scrimba.com/javascript-deep-dive-c0a/~04)
- [V2 Scrimba - JS Deep Dive - Types & Conditionals](https://v2.scrimba.com/javascript-deep-dive-c0a/~0g)
- [V2 Scrimba - JS Deep Dive - Functions](https://v2.scrimba.com/javascript-deep-dive-c0a/~0q)

### JavaScript Info on Date and Time - read this content in addition to either Odin or Scrimba
- [JavaScript.info – Working with Dates and Times](https://javascript.info/date)


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