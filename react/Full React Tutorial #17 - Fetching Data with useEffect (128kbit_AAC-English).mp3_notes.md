# Full React Tutorial #17 - Fetching Data with useEffect

## Overview

This tutorial covers the use of JSON Server with React, focusing on fetching data from an API and updating component state using the `useEffect` hook. The main objective is to learn how to manage dynamic content effectively by employing conditional templates and loading messages during data fetching operations.

## Main Ideas

1. Utilizing a running JSON Server with endpoints for different resources
2. Implementing the `useEffect` hook to fetch data once on component mount, avoiding an empty dependency array issue
3. Emptying states and setting initial values before fetching data
4. Fetching data using a `fetch` request, logging it to the console, and updating the component state with the `setBlogs` function
5. Handling errors that occur when trying to pass blogs as props due to an initial null value
6. Conditional templating using JavaScript logical operator (`&&`) within React template syntax (curly braces)
7. Removing handle delete functions, buttons, and props for local data and preparing for actual delete requests to a file in future lessons
8. Displaying a loading message while fetching data and other aspects of conditional templating in React

## Key Manipulations and Scripting

- Import necessary dependencies (React, ReactDOM, useState, useEffect)
- Create a running JSON Server
- Initialize states and set initial values for blogs to null
- Use `useEffect` hook with an empty dependency array to fetch data once on component mount
- Fetch data using a `fetch` request and update the component state with the `setBlogs` function without causing an infinite loop
- Implement conditional templating using JavaScript logical operator (`&&`) within React template syntax (curly braces)
- Remove handle delete functions, buttons, and props since they are for local data only

## Reflective or Quiz-Style Questions

1. What is the role of the `useEffect` hook in this tutorial?
2. Explain how conditional templating was implemented to avoid rendering null values in the blogs list.
3. Why was the handle delete function, button, and prop removed from the component? How will it be replaced in future lessons?