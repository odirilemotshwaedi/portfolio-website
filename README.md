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

## Issues Identified

During the website review, 17 issues were identified across HTML structure, accessibility, CSS styling, responsiveness, and form validation.

### A. HTML Structure and Metadata
1. **Missing viewport meta element:** All pages lacked the viewport meta element required for appropriate rendering on mobile devices.
2. **Missing language declaration:** The `<html>` element did not include the `lang="en"` attribute, making it difficult for assistive technologies to determine the page language.
3. **Incomplete document metadata:** Pages lacked essential metadata, including `<meta charset="UTF-8">` and descriptive meta descriptions.
4. **Missing navigation consistency:** Navigation menus were missing or inconsistently implemented across the website pages.
5. **Incorrect form input types:** Some form fields used inappropriate input types, such as `type="text"` instead of `type="email"` for email addresses.
6. **Incorrect form structure:** Form inputs lacked properly associated labels, while radio buttons and related selection controls were not logically grouped.
7. **Missing button type attributes:** Buttons did not explicitly specify their types, potentially resulting in unintended form-submission behaviour.

### B. Accessibility Issues
8. **Missing alternative text:** Some images lacked descriptive `alt` attributes, reducing accessibility for users relying on screen readers.
9. **Insufficient colour contrast:** Certain foreground and background colour combinations did not provide sufficient contrast, affecting readability.
10. **Insufficient ARIA enhancements:** Appropriate ARIA attributes and accessible relationships were missing where native HTML semantics alone did not adequately communicate the purpose or relationships of interface elements.

### C. CSS and Responsive Design Issues
11. **Footer alignment problems:** Footer content was inconsistently aligned, affecting the overall visual presentation.
12. **Unconstrained hero image:** The hero image lacked appropriate width constraints, potentially causing overflow or inconsistent presentation.
13. **Inconsistent spacing and alignment:** Margins, padding, and element alignment varied across pages, resulting in an inconsistent layout.
14. **Lack of responsive styling:** CSS lacked sufficient responsive adjustments to ensure the website displayed correctly across different screen sizes.

### D. Form Validation and Code Quality

15. **Insufficient form validation:** Form fields lacked appropriate validation rules to help enforce valid input formats and prevent invalid submissions.
16. **Inconsistent code formatting:** HTML pages contained inconsistent indentation, spacing, and formatting, reducing readability and maintainability.
17. **Inconsistent accessibility implementation:** Accessibility features were not consistently applied across pages, including accessible names, semantic relationships, and appropriate ARIA attributes where necessary.

## Fixes implemented

The following improvements were made to address the identified issues:

- Added lang="en" and <meta charset="UTF-8"> declarations to all HTML pages.
- Added viewport metadata and descriptive meta descriptions.
- Standardised navigation across the website using semantic <nav> elements and Flexbox alignment.
- Corrected form input types and introduced appropriate HTML5 validation attributes.
- Associated form labels with their respective inputs.
- Grouped related communication options using <fieldset> and <legend>.
- Added appropriate alternative text to informative images.
- Improved the table structure using <thead> and <tbody>, together with CSS styling and hover effects.
- Implemented Flexbox and CSS Grid to improve layout consistency and responsiveness.
- Added media queries to accommodate smaller screen sizes.
- Improved colour contrast and keyboard focus indicators.
-Corrected spacing, alignment, and image sizing.
- Improved HTML and CSS formatting for readability and maintainability.
- Validated the HTML and CSS using W3C validation tools to identify and correct structural and styling errors.

## Description
The website uses a simplified HTML5 structure with semantic elements instead of relying unnecessarily on generic <div> elements.

The main structural elements include:
- <header> – Contains the website header and branding.
- <nav> – Provides navigation links between pages.
- <main> – Contains the primary content of each page.
- <section> – Groups related content into meaningful sections.
- <footer> – Contains footer information.

Headings and paragraphs are organised hierarchically to improve readability and document structure. On the Projects page, individual project sections are organised using appropriate semantic elements to separate and present each project clearly.

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
├── css/
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
Reviewing and improving the starter code presented several challenges.

Some of the main issues encountered included:
- Incomplete HTML markup and document structure.
- Missing or inconsistent navigation across pages.
- Incorrect form input types and insufficient validation.
- Overuse of generic <div> elements instead of appropriate semantic HTML5 elements.
- Inconsistent CSS styling, spacing, and alignment.
- Missing hover and keyboard focus states.
- Limited responsiveness across different screen sizes.

Working through these issues improved my understanding of semantic HTML, CSS layout techniques, responsive design, and web accessibility.

Using HTML and CSS validation tools helped identify structural and styling errors. Testing the website across its pages also helped confirm that navigation, responsive layouts, hover effects, and form validation behaved as expected.

Overall, this project strengthened my ability to identify website usability issues, improve accessibility, and create a more consistent and responsive user experience.