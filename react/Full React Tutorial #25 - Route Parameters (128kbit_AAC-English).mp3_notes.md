# Full React Tutorial #25 - Route Parameters (128kbit_AAC-English).mp3

## Overview

In this tutorial, we learn how to pass dynamic values as part of a route and create a blog details component using React Router. We set up routes for the blog details component, access the route parameters, generate links dynamically, and reuse a custom hook for fetching and displaying data for the selected single blog.

## Main Ideas

1. Passing dynamic values as part of a route
2. Creating a route using Route Parameter
3. Using `useParams` hook to access route parameters in the component
4. Dynamically generating links with JavaScript template strings and curly braces
5. Removing underline from anchor tags
6. Accessing ID for each blog using props
7. Reusing a custom hook, `useFetch`, for fetching data for selected single blog

## Key Manipulations and Scripting/Coding Used

1. Creating a new functional component named `blogDetails` in the `blogDetails.js` file to be displayed when visiting dynamic routes like `/blogs/<ID>`.
2. Setting up a route for the blog details component in `app.js`, creating a new route with the path set to '/blogs/:ID'.
3. Using the `useParams` hook from React Router DOM to grab parameters or route parameters from the current route and accessing the ID by destructuring it (e.g., const { ID } = useParams()).
4. Dynamically generating links for each blog on the homepage using JavaScript template strings and curly braces (`<a href={`/blogs/${blog.id}`}>`).
5. Removing underline from anchor tags in the `index.css` by adding `text-decoration: none;`.
6. Accessing the ID for each blog from the individual blog details component using `this.props.match.params.id`.
7. Reusing a custom hook, `useFetch`, to fetch and display data for the selected single blog in the individual blog details page.

## Reflective/Quiz-Style Questions

1. What is the purpose of using a colon followed by a name (e.g., /blogs/:ID) in a route?
2. How can you access the ID for each blog using JavaScript template strings and curly braces in generating links for each blog on the homepage?
3. In which file would you add the `text-decoration: none;` style rule to remove underlines from anchor tags, and why is it necessary?