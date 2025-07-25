# ## The Odin Project Links:

## Overview

No overview provided

## Learning Objectives

Learning objectives will be defined as the lesson progresses.

## Topics Covered

Topics will be covered as the lesson progresses.

## Status

pending

## Assignment

Assignment for Lesson 7

### Objective

No objective specified

### Expected Capabilities

Expected capabilities will be defined as the lesson progresses.

### Instructions

Instructions will be provided when the lesson is generated.

### Tasks

#### Task 1: Task 1

### Get organized and write some code!
   - [ ] In your GitHub repository, if you have not yet merged your pull request from two weeks ago, merge your open lesson-5 pull request by going to the "Pull Requests" tab of your repository.  Click on your open pull request, then click on the green 'Merge Pull Request" and confirm the merge.  This will update your main branch with the work you did on your lesson-5 branch.
   - [ ] Open your code editor and, in the terminal, make sure you're on your main branch.  If you're still on your lesson-5 branch, you can switch to your main branch by using the git command `git checkout main`.  
   - [ ] Update your local main branch to include your lesson-5 work by pulling your changes from your GitHub repository main.  Use the following git command in your terminal to do this: `git pull origin main`.  Doing this copies the lesson-5 work you merged to main and pulls it to your local machine so now all your branches should be identical on your local machine.
   - [ ] Still in your terminal, create a new local branch to keep track of just the work you'll do for this assignment by running `git checkout -b lesson-7` in the terminal.  

### Assignment: Task List / Deliverables
Open your index.html file.  Add "boilerplate" HTML code as a starting point that includes all the required elements and meta tags.  While copy and pasting is common practice, this week we want you to write all the boilerplate code from scratch so you understand the parts of it and what their functions are.  Each line of the boilerplate HTML code is broken down below.  REMINDER: HTML uses code called "tags" and "elements". In HTML, an element consists of a "start tag", some content, and an "end tag".  So when describing the <title> element, for example, we're referring to this: `<title>Your Title</title>` Also, keep in mind some HTML elements are "self-closing", meaning that they have one tag that opens and closes at the same time (e.g. `<meta name="description" content="Your description" />`. In the Body and Additional Elements sections of these instructions you'll find the bulk of the actual site content (what the user will see when they view your page) listed.

#### HTML Boilerplate

##### Doctype
First let's define what type of document the browser will be reading.
   - [ ] Define the document type at the top of the file by typing in `<!DOCTYPE html>` on line 1.

##### Head Element
The "head" of an HTML document contains all the page's meta information, such as title and description.  This information helps with web searches and displays the page title in the browser tab.
   - [ ] Before your name, but after the `<html>` opening tag, insert a `<head>` element.
   - [ ] Inside the <head> element, add a <title> element to title your webpage (ex. Maria Santiago's Portfolio)
   - [ ] Below your <title> element, add additional <meta> elements (at least two) from the meta elements you've learned about and/or find at this resource: [W3Schools HTML Head](https://www.w3schools.com/html/html_head.asp))

##### Body Element
The "body" of an HTML document contains all the page's visible content.
   - [ ] After the closing </head> tag, begin the body of your page by adding the opening `<body>` element. 
   - [ ] Close the body of your page by adding the closing `</body>` element right before the closing `</html>` tag
   - [ ] Make sure all of the following content is inside the `<body>` tags, in this order:
     - [ ] Your name in an `h1` element
     - [ ] The word 'About' in an `h2` element
     - [ ] A paragraph about you in a `p` element
     - [ ] The word 'Experience' in an `h2` element
     - [ ] Your listed experiences in a `ul` element, with each individual item in a `li` element.  Experiences can be courses you've taken, coding/tech languages you've learned, technologies you've worked with, or other experiences that highlight your value.
     - [ ] The word 'Connect' in an `h2` element
     - [ ] Your social media links in `a` elements, and you can also wrap them in `ul` and `li` tags if you wish.  Include at least two, your GitHub and LinkedIn profiles.  You can include more (Facebook, YouTube, Instagram, WhatsApp, TikTok, Discord, X, etc.) if you like.

#### Additional Elements
HTML describes the structure of a webpage using various semantic elements, such as: headings, paragraphs, lists, and more, as you just saw by writing content for the body of your page.  Now let's organize that content...
   - [ ] Wrap each of the About, Experience, and Connect sections in a `<section>` element.  You'll use this later when you style your webpage to stay organized and apply different style settings to each of the different settings.
   - [ ] Give each of these sections an "id" property with the same name as the section.  Example:  The About section would look like this:

``` jsx
<section id="About">
   <h2>About</h2>
      <p>This is a paragraph about me.  Here's more info about me.</p>
</section>
```
   - [ ] STRETCH GOAL (optional):  Feel free to use even more HTML elements by adding images, navigation menus, etc.

**_By the end of these instructions, your index.html page should have boilerplate code that allows your web browser to identify what kind of document it's displaying and the meta data about your page (ex. title, keywords, etc.). You should have your Name, and three sections: (1) an About header with a paragraph about yourself, (2) an Experience header with a list of your experiences, and (3) a Connect header with at least two links.  All of this should be written in HTML in your index.html file._**

### Backup to the cloud
Once you've made the above changes to your html file, follow the below instructions to push a copy from your local machine like you did at the end of last assignment.  Make sure your code gets copied to GitHub by adding changes to staging, committing the staged changes, and pushing them from your local machine to GitHub:
   - [ ] Check the status of the changes you just made (editing the index.html file) by running `git status` in your terminal
   - [ ] Stage all your changes for commit by running `git add .` in your terminal
   - [ ] Run `git status` again to see how things have changed.  You should get a response indicating changes staged for commit.
   - [ ] Create a commit message for reference.  You can use a different message if you wish.  Run `git commit -m "boilerplate and content added"`
   - [ ] Push these changes to your GitHub repository from your local computer by running `git push`

### Submit Assignment
Now let's make sure that lesson branch will be reviewed.
   - [ ] Go to your GitHub repository page in your web browser now, and you should see a "lesson-7 has a recent push" notice with a green "Compare & pull request" button.  Click that button
   - [ ] Feel free to put notes to yourself or notes for your reviewer in the description (be sure you're including any questions to your reviewer in your assignment submission form though!) and click the green "Create pull request" button.
   - [ ] Copy the address of your pull request page (should look like `https://github.com/yourUsername/name-classname/pull/2`) and paste it into your assignment submission form.

### What next?
   - If you're on track with class, wait to get feedback and/or the email notice that your assignment review is complete before confirming and merging your pull request to the main branch.
   - If you're behind or are working ahead:  
     - if you're confident your work is accurate, merge your pull request and continue working through class.
     - if you're not sure about your work this week, schedule a 1:1 session with a mentor and review your work together before merging.


```

```

### Submission Instructions

Please submit on time

### Checklist

Checklist will be provided when the lesson is generated.

### Check for Understanding

Understanding checks will be provided when the lesson is generated.

## Subsections

### Lesson 7

Remember to please go to each link in this list and read through the content on that page. If there are links you are redirected to as you read/work through the content, follow those links as well and read the content there also.

**Note:** The Scrimba course does not cover as much detail as the Odin Project on these topics so only those video lessons as a review of the basics of HTML.

### The Odin Project Links:
- **[The Odin Project – How Does the Web Work?](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/how-does-the-web-work)**
- **[The Odin Project – Introduction to HTML and CSS](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/introduction-to-html-and-css)**
- **[The Odin Project – Elements and Tags](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/elements-and-tags)**
- **[The Odin Project – HTML Boilerplate](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/html-boilerplate)**
- **[The Odin Project – Working with Text](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/working-with-text)**
- **[The Odin Project – Lists](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/lists)**
- **[The Odin Project – Links and Images](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/links-and-images)**
- **[The Odin Project - Forms](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-form-basics)**
- **[The Odin Project - Semantic HTML](https://www.theodinproject.com/lessons/node-path-advanced-html-and-css-semantic-html)**
- **[The Odin Project - Introduction to Accessibility](https://www.theodinproject.com/lessons/node-path-advanced-html-and-css-introduction-to-web-accessibility)**

### Scrimba Links:
- **[Scrimba - HTML & CSS Crash Course](https://v2.scrimba.com/html-css-crash-course-c02l/~00)**
- **[Let’s write some HTML!](https://v2.scrimba.com/html-css-crash-course-c02l/~04)**
- **[strong and emphasis](https://v2.scrimba.com/html-css-crash-course-c02l/~05)**
- **[File naming and organization](https://v2.scrimba.com/html-css-crash-course-c02l/~06)**
- **[Anchors and Attributes](https://v2.scrimba.com/html-css-crash-course-c02l/~07)**
- **[Lists](https://v2.scrimba.com/html-css-crash-course-c02l/~0c)**
- **[Images](https://v2.scrimba.com/html-css-crash-course-c02l/~0d)**

### HTML

*Hypertext Markup Language (created in 1989)*, commonly called *HTML*, is a programming language that is used to create the structure of a web page. The basic idea of HTML is that the brackets < > surrounding the code of a web page tell the web browser what information it's working with.

At its core, hypertext is digital text that can link to other places, such as one website connecting to another. HTML, a markup language, uses tags like **`<head>`** and **`<body>`** to structure web content in a way that browsers can display. Unlike technical programming code, HTML uses human-readable words, making it user-friendly for web content creation.

HTML is the foundational component of a website adding these elements to a web page:

- Text: Words and written content
- Media: Images, videos, and other visual or auditory elements
- Links: Clickable paths to other places, like other websites
- Containers: Elements that are used to give web pages structure for layout purposes

### Tags vs Elements

An HTML element is often made up of two **_tags_**: an _opening tag_ and a _closing tag_ (sometimes called a _begin tag_ and an _end tag_, respectively). The opening tag begins the HTML element, and it's enclosed in brackets <>.

An HTML **_element_** consists of two tags: an opening tag and a closing tag (such as `<h1>` and `</h1>`). The closing tag will always have a /, which signifies the end of an element. HTML text can be grouped into headings or paragraphs.


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