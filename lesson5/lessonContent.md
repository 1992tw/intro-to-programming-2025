# Get ready for git!

## Overview

No overview provided

## Learning Objectives

Learning objectives will be defined as the lesson progresses.

## Topics Covered

Topics will be covered as the lesson progresses.

## Status

pending

## Assignment

Assignment for Lesson 5

### Objective

No objective specified

### Expected Capabilities

Expected capabilities will be defined as the lesson progresses.

### Instructions

Instructions will be provided when the lesson is generated.

### Tasks

#### Task 1: Task 1

### Prepare to code!
If you don't already have an IDE you prefer to use, and if you haven't yet completed the "Get ready for git!" section from last week's lesson, do so now.  That involves downloading and installing Visual Studio Code and getting yourself familiar with it and it's tools.  So you don't have to jump back to last week, here is the [link to download Visual Studio Code](https://code.visualstudio.com/) and the video on how to find your way around it:
[Visual Studio Code Info Session with Shawn Clary](https://www.youtube.com/watch?v=R8lusLkuWJQ)

Once you have your local machine setup, it's time to create a repository in your cloud-based git repository on GitHub...

### Create a new repository 
Create a new repository in your GitHub account by following these steps:
   - [ ] Go to your GitHub page and click the Repositories tab
   - [ ] Click the green "New" button in the top right
   - [ ] Fill in the fields to give your repository a name (use your name-**_classname_** as the name example: `maria-santiago-jupiter`) and description (example: portfolio project for Intro to Programming course with Code the Dream)
   - [ ] Be sure PUBLIC is selected and check the "Initialize this repository with: Add a README file" check box.
   - [ ] Click "Create Repository"

### Clone to your local machine
Copy the repository you just created in GitHub to your local computer by following these steps:
   - [ ] On the main Code page of your repository, click the green "Code" button
   - [ ] Your lesson walked you through setting up an SSH key with GitHub.  You should select "SSH" as the Local Clone type (not HTTPS or GitHub CLI).
   - [ ] Click the copy button (two overlapping squares icon) to copy your repository address.  It should look like `git@github.com:yourUsernameHere/firstname-lastname-class.git`
   - [ ] Go to your IDE terminal or your computer terminal.  Make sure you're in the proper directory for where you want to create and store files for your work (ex. your Desktop or a CodeTheDream folder).  Then run `git clone <repository>` where "\<repository\>" is replaced with the last portion you copied in the last step.

### Get organized and write some code!
   - [ ] Navigate into the directory you just cloned by running `cd <name-classname>` in the terminal where the <name-classname> portion is the name of your repository.
   - [ ] Create a new local branch to house just the work you'll do for this assignment by running `git checkout -b lesson-5` in the terminal
   - [ ] Open the README.md file in your code editor and add your full name.
   - [ ] Create a new file in your project directory (same level as your README.md file) and title it `index.html`

### Backup to the cloud
Make sure your code gets copied to GitHub by adding changes to staging, committing the staged changes, and pushing them from your local machine to GitHub.
   - [ ] Check the status of the changes you just made (editing the readme.md file and making a new index.html file) by running `git status` in your terminal
   - [ ] Stage all your changes for commit by running `git add .` in your terminal
   - [ ] Run `git status` again to see how things have changed.  You should get a response indicating changes staged for commit.
   - [ ] Create a commit message for reference.  Run `git commit -m "my first commit"`
   - [ ] Push these changes to your GitHub repository from your local computer by running `git push origin lesson-5`
   - [ ] **NOTE:** if you get a "fatal: The current branch..." error message.  READ the message and follow the instructions in that message to confirm that you push your work to your GitHub account.

**_By this point, you should have a local folder on your machine that has a README.md and index.html file, and your lesson-5 branch of your GitHub repository should also have your README.md and index.html files.  You can find your lesson-5 branch by clicking on the main button in your GitHub repository.  You should see the list of all your branches (main and lesson-5) there.  See image below for example:_**

![branch drop down in GitHub repository](https://github.com/Code-the-Dream-School/intro-to-programming-2024/blob/5e3d47bcdc1ad5b6a72a75cc5694f459ce0b5024/mainBranch.png?raw=true)

### Submit Assignment
Now let's make sure that lesson branch will be reviewed.
   - [ ] Go to your GitHub repository page in your web browser now, and you should see a "lesson-5 has a recent push" notice with a green "Compare & pull request" button.  Click that button
   - [ ] Feel free to put notes to yourself or notes for your reviewer in the description (be sure you're including any questions to your reviewer in your assignment submission form though!) and click the green "Create pull request" button.
   - [ ] Copy the address of your pull request page (should look like `https://github.com/yourUsername/name-classname/pull/1`) and paste it into your assignment submission form.

### What next?
   - If you're on track with class, wait to get feedback and/or the email notice that your assignment review is complete before confirming and merging your pull request to the main branch.
   - If you're behind or are working ahead:  
     - if you're confident your work is accurate, merge your pull request and continue working through class.
     - if you're not sure about your work this week, schedule a 1:1 session with a mentor and review your work together before merging.
    
### REMINDER
If you are completing work on the Algorithms Stretch Goal this lesson, you should go to your "Lesson 4 - Array Methods and Algorithm Stretch Goal" repl from last week's coding assignment and work on the practice exercises below the "Stretch Goal on Algorithms Below" header in the code.


```

```

### Submission Instructions

Please submit on time

### Checklist

Checklist will be provided when the lesson is generated.

### Check for Understanding

Understanding checks will be provided when the lesson is generated.

## Subsections

### Lesson 5

# Get ready for git!

This week you'll be learning about git version control, and you'll start using a cloud-based git repository program called GitHub to complete your coding assignments.  There are several programs developers use as they build, test, and deploy/publish their code.  While you're welcome to use any tools/combination of tools you prefer, we recommend using [Visual Studio Code](https://code.visualstudio.com/).  Visual Studio Code is an IDE (Integrated Development Environment).  IDEs are helpful programs that combine several tools (a text editor, the command line/terminal, file organization, and more) into one program.  If you aren't currently using an IDE of your own preference, you should watch the video below and install Visual Studio Code and suggested extensions in the video before you start this week's assignment.

[Visual Studio Code Info Session with Shawn Clary](https://www.youtube.com/watch?v=R8lusLkuWJQ)

Remember to please go to each link in this list and read through the content on that page. If there are links you are redirected to as you read/work through the content, follow those links as well and read the content there also.

- **[The Odin Project – Text Editors](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/text-editors)**
- **[The Odin Project – Command Line Basics](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/command-line-basics-web-development-101)**
- **[The Odin Project – Setting Up Git](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/setting-up-git)**
- **[The Odin Project – Introduction to Git](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/introduction-to-git)**
- **[The Odin Project – Git Basics](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/git-basics)**



***

## _**STRETCH GOAL (OPTIONAL): Intro to Algorithms**_
- **[Scrimba](https://v2.scrimba.com/javascript-interview-challenges-c02c/~00) - JavaScript Interview Challenges**
- Watch and practice the first 5 videos (with solutions). Try to solve each algorithm before you watch the solution. The more you practice the more comfortable you will you get, which is good preparation for job interviewing.

### Algorithms

Think about it: you've been low-key using algorithms since your elementary school days. Yep, those step-by-step instructions for multiplying numbers? Bingo, those are algorithms!

Now, let's break it down a bit. An **algorithm** is like a super precise recipe for solving a computer puzzle. Simple, right? But wait, what's a **computational problem**? Well, it's basically a riddle that a computer can help us solve. For example, think about sorting a jumbled mess of numbers into a neat little order. That's a computational problem.

So, when we talk about problems, we're talking about spelling them out really clearly. That means telling the computer exactly what it's working with – the stuff going in, what's supposed to come out, and how they're all connected. This is similar to using AI as well. You have to write a very detailed prompt when communicating with AI or you may get missing or incorrect information back.

An algorithm is like a secret recipe that lays out a series of steps. If you stick to those steps exactly as they're written, voilà, you'll solve the problem! It's like having multiple paths to victory in a game – as long as you follow the rules, you'll win!

1. Read this [article](https://www.theodinproject.com/lessons/javascript-a-very-brief-intro-to-cs) on Odin. 
2. Read this [article](https://www.geeksforgeeks.org/introduction-to-algorithms/).  We won’t be getting into the types of algorithms but it’s a good overview of how algorithms are part of a developer’s daily life. 
3. Once again, same info, but [a video](https://www.khanacademy.org/computing/computer-science/algorithms/intro-to-algorithms/v/what-are-algorithms) from Khan Academy.



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