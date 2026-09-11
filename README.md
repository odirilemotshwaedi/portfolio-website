# Overview Portfolio Website

This is the codebase for my portfolio website project, is a personal showcase of my skills, projects that i have worked on and professional background, I designed it to present my works in an appealing and accessible way.

## What's Included

- index.html - Home page with a welcoming hero section that introduces me as a web developer
- about.html - About page highlighting my background skills and includes my personal photo for clients to get insights into my expertise.
- projects.html - Projects page displaying screenshots of some of the projects i have worked on.
- contact.html - Contact page with a functional a form where users can get in touch with me by filling in their details and choosing which communication method, they prefer to be reached.
- CSS/styles.css - Stylesheet of the entire website
- images/ - Placeholder folder for images
- design/ - place holder for wireframe document and issues document
- screenshots/ - Placeholder for screenshots of the completed site.

## Issues Found
1.  A viewport meta element was not specified on all pages
2.  The HTML tag was not declared with <lang="en"> which cause an error.
3.  Errors found on the image tags do not have title attributes that clearly describe the image.
4.  Navigation was missing across pages, so I used <nav> elements together with <a> tags to ensure user flow.
5.  Images did not have alternative texts
6.  Input type of a form declared email as a type of text so I changed it to email, I then included other fields such as id tags to link the label to the input, required and checked to ensure validation, min length for the name input type, and pattern for email and phone number as well.
7.  I also included labels for all input types, a radio box for the communication type and a select type.
8.  The button type attribute was not set.
9.  The charset meta element was not used on all HTML pages
10. The document had poor colour contrast error.
11. The footer was not wrongly aligned
12. The colour contrast was poor
13. The hero image had sizing issues with no limit to its width, when the web page expands it also expands covering the entire screen
14. The spacing was also not consistent and there was also alignment issues identified.
15. The were no responsive adjustments declared in the CSS file.
16. There we inconsistencies in the formatting and indentation of the pages.

## Fixes implemented

- I added lang="en" on all HTML tag of every page to remove the errors found on the startup code and added <nav> elements on all pages of the website for navigation also used flexbox on the <header> to align the navigation items with the header title.
- On the form I fixed the input types, by assist each type of each fields such as (type="email") in the email input field, I also added validations attributes such as required to make it a must for a user to enter something input field and not leave it blank, pattern for email and phone input fields so that the user can know when they have missed a character, min and max lengths for fields such as name where a client should enter something with more than 2 characters as a name.
- I added alt attributes that were missing on all image tags and a focus state for images in the projects page for visibility of a possible selection.
- There was not table in the starter code so I included it and used <thead> and <tbody> for the structure/layout of the table, I styled the table with boarders with header rows and hover effect on the table rows.
- I implemented flexbox and grid for responsive layout for pages such as hero ad projects, i applied responsive media queries as well to adjust padding and layout on screens smaller that desktop.
- I also used W3C for validation on the HTML and CSS to catch structural errors.

## Description
My final HTML structure and selectors used I decided to go with a less complex approach where I only used h2, h3 p on texts, I used HTML5 tags (header, main, nav, footer and section) and removed the div elements on each page. I also used section elements more on the projects page to clearly separate and add more functionality to the project images included in the code.

## Explanation of CSS approach
- The layout I went with the flexbox to align the title and the navigation well and neatly on every page and i went with the grid in the projects page to create a responsive card layout of the images so that they can be adaptive to the size of the screen.
- I added media queries @media (max width: 768px) to adjust padding and layout for screens that are smaller that desktop and ensured that images scale with a maximum width of 100% and a hight of auto to prevent them from overflowing.
- In terms of styling i added a box model to demonstrate margins, padding and boarders I used, i also used inline examples and block examples to demonstrate the difference in elements displayed.
- I used combination selectors as well to style elements based on their relationship
- I styled the form as well to make it look appealing and with enough space where the user inputs data, i uses validations on the form as well on the client side of the website then added a focus style to highlight the active fields, I included a hover effect as well on the navigation links and on the submit button of the form to provide a use with feedback.
- I regards to accessibility I aligned the contrast by using a dark background with a light text and cleared focus outlines for keyboard navigations, I then styles my <h1> <h2> with uppercase text for emphasis and used italics style on all paragraphs for readability.

## Accessibility improvements made
- I used HTML semantic structure<header>, <nav> <main>, <section>, <footer> for logical page flow. also added a <fieldset> to group the inputs in the communication section of the form.
- I also made sure that I every <input> and <select> had a <label> with a for that matched it to describe the purpose of each field.
- I added alt attributed on all image tag to improve usability.
- I also included an active states effect on the navigation tabs and hover effect on buttons and table select fields, I added a forces state on the inputs of the form together with shadows.
- In regard to the responsive design of the website, I included media queries and flexible layouts such as grid, flexbox and block so that the content adapts to the screen of the device where the website is used.

## Instructions on how to view locally
- Cloning the repo into your local machine.
- Open the cloned project folder in your machine.
- Double-click/right click the index.html document or any of the HTML document in the folder then left click on the "Open with" option and click on the browser that appears on the list to view the website.
- Use the navigation tabs (Home, About, Contact and Project) at the top of each page to browse through every page of the website.

- Structure
portfolio-website/
│
├── index.html
├── about.html
├── projects.html
├── contact.html
├── CSS/
│   └── styles.css
├── images/
│   ├── hero.jpg
│   ├── profile.jfif
│   ├── project1.png
│   ├── project2.png
│   └── project3.png
├── design/
│   ├── wireframe.pdf
│   └── issues-identified.pdf (or .txt)
├── screenshots/
│   ├── aboutpage.png
│   ├── before-after.png
│   ├── contactpage.png
│   ├── homepage.png
│   └── projectpage.png
└── README.md

## Screenshots
●   All four pages of your completed website
●   Your HTML form (showing improvements)
●   Your styled table
●   Navigation menu with hover states
●   Before/After comparison of at least one page (optional but recommended)

## Reflection

I encountered a couple of challenges as I worked through the code.
first there were multiple Doctype errors which were cause due to incomplete coding but I managed to fix it by including the lang="en". 
Then there were no navigations between the page which I then added using the <nav> element on every HTML page.
thirdly i noticed that the form in the document had input tags but they were missing a few details like changing the type of an email from "Text" to "email", adding required on all fields that should not be left blank, i also included pattern on email and phone input fields so that the user can enter them in the correct order and not make mistakes.
I then changed all the parent <div> tags to their proper HTML5 semantic such as header, main, footer, section etc, 
I then moved over to CSS where there were no hovers states, consistent alignment, I added and fixed then implemented CSS grids and flexbox for responsive layouts, I demonstrated a box model, combination selectors, pseudo classes etc and added project cards.
Although some errors were not that obvious, I used W3C to validate HTML and CSS errors to find other structural issues and I then tested hover and input states of the form to make sure they are working.
