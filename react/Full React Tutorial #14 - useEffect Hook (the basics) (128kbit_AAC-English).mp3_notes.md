# Full React Tutorial #14 - useEffect Hook (the basics)

## Overview

In this tutorial, we delve into the use of the `useEffect` hook in React, a powerful feature that enables running a function upon every render of a component. This hook is instrumental for handling side effects such as fetching data, setting up subscriptions, and manipulating the DOM.

## Main Ideas

1. Import the `useEffect` hook from 'react' and place it above the return statement in your functional component.
2. Pass a function as an argument to `useEffect`. This function will run every time there is a re-render of the component.
3. The function runs initially when the component loads for the first time, and subsequently whenever the data changes.
4. Be cautious about modifying state within `useEffect` to avoid creating an infinite loop of renders.

## Key Manipulations and Scripting/Coding Used

1. Import `useEffect` from 'react' at the beginning of your functional component:
   ```javascript
   import React, { useEffect } from 'react';
   ```
2. Use `useEffect` within your functional component above the return statement:
   ```javascript
   function MyComponent() {
     useEffect(() => {
       // Your code here
     });

     // Rest of your component
   }
   ```
3. Pass a function as an argument to `useEffect`. This function will run every time there is a re-render:
   ```javascript
   function MyComponent() {
     useEffect(() => {
       console.log('Component has been rendered!');
     });

     // Rest of your component
   }
   ```

## Reflective/Quiz-Style Questions

1. What does the `useEffect` hook enable in React?
2. When does the function passed to `useEffect` run for the first time, and when does it subsequently run?
3. Why should you be cautious about modifying state within `useEffect` and what can happen if you don't?