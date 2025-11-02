# Full React Tutorial #6 - Adding Styles

## Overview

This tutorial focuses on adding CSS styles to React components. The two main approaches discussed are using separate CSS files for different components, or using CSS Modules or Styled Components for scoped styling. In this specific project, we utilize multiple CSS files: `app.css` and an `index.css` global style sheet.

## Main Ideas

1. Importing and applying a global style sheet (`index.css`) that contains all necessary CSS styles.
2. Adding Google Fonts to the project and applying base styles for general elements, navbar, links, and other components.
3. Modifying the color and styling of `h1` in the navigation bar and links, centralizing content within the home component, and using inline styling using JSX.

## Key Manipulations and Scripting or Coding Used

- Deleting the `app.css` file and importing an `index.css` file into the root (`index.js`) component to add styles to the head of the webpage.
- Changing the color of the `h1` in the navigation bar, styling links, and applying hover effects.
- Centralizing content within the home component by setting maximum width, margins, and padding.
- Inline styling using JSX by creating an object with key-value pairs for CSS properties within the style attribute in JSX, using camel case CSS property names (e.g., backgroundColor), and wrapping the entire object in curly braces.

## Reflective or Quiz-Style Questions

1. What are the two main approaches discussed for adding CSS styles to React components? Explain the differences between them.
2. How can you change the color of a specific `h1` in the navigation bar using inline styling with JSX?
3. Centralize the content within another component similar to what was done with the home component. What properties should be set, and why?