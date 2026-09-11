# Overview Portfolio Website

This project is a personal portfolio website designed to showcase my skills, projects, and professional background. It presents my work in a clean, appealing, and accessible way.

## What's Included

- index.html – Home page with a hero section introducing me as a web developer.
- about.html – Highlights my background, skills, and includes a personal photo.
- projects.html – Displays screenshots and descriptions of projects.
- contact.html – Functional form for users to get in touch and select communication preferences.
- css/styles.css – Stylesheet for the entire site.
- images/ – Placeholder for images.
- design/ – Wireframe and issues documentation.
- screenshots/ – Screenshots of completed pages.

## Issues Found
1. Missing viewport meta element on all pages.
2. <html> tag lacked lang="en".
3. Image tags missing descriptive title attributes.
4. Navigation missing across pages.
5. Images without alt text.
6. Form input types incorrect (e.g., email set as text).
7. Labels missing for inputs; radio and select elements not grouped properly.
8. Button type attribute not set.
9. Missing <meta charset="UTF-8"> on some pages.
10. Poor color contrast.
11. Footer alignment issues.
12. Hero image lacked width constraints.
13. Inconsistent spacing and alignment.
14. No responsive adjustments in CSS.

## Fixes implemented

- Added lang="en" and <meta charset="UTF-8"> to all pages.
- Standardized navigation with <nav> and Flexbox alignment.
- Corrected form input types and added HTML5 validation.
- Linked labels to inputs; grouped communication options with <fieldset>.
- Added descriptive alt attributes to all images.
- Introduced a styled table using <thead> and <tbody> with hover effects.
- Implemented Flexbox and CSS Grid for responsive layouts; added media queries for smaller screens.
- Improved color contrast and focus states for accessibility.
- Validated HTML and CSS using W3C tools to catch structural errors.

## Description
I used a simplified HTML5 structure with semantic tags (header, main, nav, section, footer) instead of unnecessary <div> elements. Headings (h2, h3) and paragraphs (p) were kept minimal. On the Projects page, <section> elements separate and style each project.

## Explanation of CSS approach
- Flexbox for aligning headers and navigation.
- Grid for responsive project cards.
- Media queries for mobile adjustments.
- Box model demonstration with margins, padding, and borders.
- Combination selectors for contextual styling.
- Form styling with spacing, hover effects, and focus states for usability.
- Accessibility improvements with high-contrast colors, keyboard focus outlines, and semantic emphasis.

## Accessibility improvements made
- Semantic structure (<header>, <nav>, <main>, <section>, <footer>).
- Grouped form inputs with <fieldset> and <legend>.
- Labels linked to inputs for screen reader support.
- Added descriptive alt text for all images.
- Hover/active states for navigation and buttons.
- Focus states with shadows for form inputs.
- Responsive design with Flexbox, Grid, and media queries.

## Instructions on how to view locally
- Cloning the repo into your local machine.
- Open the cloned project folder in your machine.
- Double-click/right click the index.html document or any of the HTML document in the folder then left click on the "Open with" option and click on the browser that appears on the list to view the website.
- Use the navigation tabs (Home, About, Contact and Project) to browse the website.

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
|   ├── form-validation.png
│   ├── homepage.png
│   └── projectpage.png
└── README.md

## Screenshots
●   All four pages of your completed website
●   HTML form (showing improvements)
●   Styled table
●   Navigation menu with hover states
●   Before/After comparison of at least one page.

## Reflection
Debugging the starter code presented several challenges:
●  Multiple <!DOCTYPE html> errors due to incomplete markup.
●  Missing navigation across pages.
●  Incorrect form input types and lack of validation.
●  Overuse of <div> instead of semantic HTML5 tags.
●  CSS lacked hover states, alignment, and responsiveness.
Validation tools helped identify subtle errors, and testing confirmed hover and input states worked correctly.
