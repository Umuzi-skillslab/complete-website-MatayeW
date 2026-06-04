## Portfolio Website: Capstone Project Overview

-By Mataye Whitelhane

This project is a fully functional multi-page portfolio website edited using HTML and CSS. The goal was to debug and complete an incomplete starter codebase provided. The final website demonstrates proper semantic HTML structure, responsive layout techniques, and professional styling.

My Portfolio website consists of four pages: `Home`, `About`, `Projects`, and `Contact`. Each page is can be accessed through the navigation menu and was styled using a single CSS file.

## Issues Found

The starter codebase contained numerous issues across HTML and CSS files. Key problems included:

- Overuse of `<div>` elements instead of HTML semantic tags
- Missing navigation menus and inconsistent linking between pages
- Missing required metadata
- Images without alt attributes
- Missing data table on the About page
- Incomplete Projects page (missing content)
- Contact form lacking labels
- Accessibility issues
- CSS missing navigation styling and selector variety
- No pseudo-classes (`:hover`, `:focus`)
- Poor colour contrast
- No table styling
- Poor code format
- lack of meaningful comments

## Fixes Implemented

- Replaced `<div>` elements with semantic HTML elements (header, nav, main, section, article, footer)
- Added consistent navigation menu across all pages with working links
- Included required metadata (lang, viewport) on all pages
- Added descriptive alt text to all images
- Created a structured data table on the About page using thead and tbody
- Completed the Projects page with multiple project entries
- Built a fully functional contact form with:
  -Labels for all inputs
  -Multiple input types (`text`, `email`, `select`, `radio`, `checkbox`, `textarea`)
  -HTML attributes (`required`, `minlength`, `maxlength`)
- Improved accessibility with proper form structure and navigation labels
- Expanded CSS to include multiple selector types (element, class, ID, descendant, pseudo-class, attribute)
- Added hover and focus effects for interactive elements
- Improved colour contrast for readability
- Applied box model properties (margin, padding, border) throughout
- Styled table with borders, spacing, and alternating row colours
- Improved layout using Flexbox for navigation and alignment
- Cleaned and organised code with consistent indentation and comments

## HTML Structure and Semantic Choices

`<header>` for page titles and navigation
`<nav>` for consistent navigation menus
`<main>` for main content
`<section>` for grouping related content
`<article>` for individual project items
`<footer>` for contact information

This structure improves readability and accessibility

## CSS Styling Approach

- Used multiple selector types (`element`, `class`, `ID`, `descendant`, `pseudo-class`, `attribute`)
- Applied consistent spacing using `margin` and `padding`
- Used `borders` and `border-radius` for structure
- Styled navigation using `Flexbox` and `hover` effects
- Created a responsive layout
- Styled forms with clear visual focus
- Styled tables with `borders` and `alternating row colours`
- consistent colour scheme
- Accessibility Improvements

## Accessibility improvements:

- Added alt text to all images
- Associated labels with all form inputs
- Used semantic HTML elements for better screen reader support
- Added HTML validation attributes to forms
- Ensured sufficient colour contrast for readability
- Added navigation labels for assistive technologies

## How to View the Website

- Download or clone the repository
- Open the project folder
- Open index.html in any web browser
- Navigate between pages using the menu

## Screenshots

The following screenshots are included in the screenshots folder:

- Homepage
![homepage screenshot](<New Screenshots/homepage.png>)

- Homepage(bottom) -the bottom section of the homepage
![screenshot of bottom of homepage](<New Screenshots/homepage(bottom).png>)

- About page (with table)
![about page screenshot](<New Screenshots/about.png>)
- About page table (hover state)
![screenshot of about page table with hover state](<New Screenshots/about(hover).png>)

- About(bottom)-the bottom of the about page below the table
![screenshot of bottom of about page](<New Screenshots/about(bottom).png>)
- Projects page
![screenshot of projects page](<New Screenshots/projects.png>)

- Projects(bottom)-the bottom of the projects page
![screenshot of bottom of projects page](<New Screenshots/projects(bottom).png>)

- Contact page
![screenshot of contact page](<New Screenshots/contact.png>)

- Contact form 
![screenshot of form on contact page](<New Screenshots/contact form.png>)



## Reflection

My main challenge in this project was identifying and fixing hidden errors in the starter code. Many issues were not immediately obvious, like the accessibility and validation errors. Debugging required careful attention to detail and frequent use of validation tools.

Overall, this project improved my understanding of semantic HTML, accessibility best practices, and CSS layout techniques. It also strengthened my debugging skills and ability to transform incomplete code into a professional final product.
