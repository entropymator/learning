# Full React Tutorial #22 - Exact Match Routes (128kbit_AAC-English).mp3

## Overview

In this tutorial, we learn how to create a new route for a web form to add a new blog using the `exact` prop in React Router. This helps prevent issues where React Router matches the route to the first one it finds, even if it is nested within another route.

## Main Ideas

1. Creating a stateless functional component named `create` for adding a new blog.
2. Adding a new route using the `switch` component to render the `create` component when the user goes to `/create`.
3. Implementing the `exact` prop in the new route to ensure it matches only when it is exactly at the URL, not just inside the URL.
4. Understanding the importance of the `switch` component for managing routes efficiently and ensuring that only one route component shows in the browser at any one time.

## Key Manipulations and Scripting or Coding Used

1. Created a new stateless functional component named `create`.
2. Added a new route inside the switch component, with the path set to `/create`.
3. Added an `exact` prop to the new route to make it match only when it is exactly at the URL, not just inside the URL.

## Reflective or Quiz-Style Questions

1. Why was the initial implementation of the new route causing issues with React Router?
2. What role does the `switch` component play in managing routes efficiently in a web application using React Router?
3. How can you avoid sending requests to the server for every click when using links in a React application?