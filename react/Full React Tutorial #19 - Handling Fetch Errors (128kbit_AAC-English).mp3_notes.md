# Full React Tutorial #19 - Handling Fetch Errors

This study notes cover a tutorial on handling errors within a component (Home Component) during data fetching, focusing on network errors and server-sent errors.

## Overview
The lecturer demonstrates how to manage and handle errors in a React application, specifically during API calls using the Fetch function. The tutorial covers error handling techniques, storing errors in state, conditional rendering, and updating the state in response to errors or successful data fetching.

## Main Ideas
1. Handling network errors by adding a catch block to the fetch operation and simulating them by canceling the process from Jason's server using `ctrl C`.
2. Identifying and handling server-sent errors by checking the response object received from the server and throwing an error with a custom message when necessary.
3. Storing errors in state by creating a `const [error, setError]` to store errors and conditionally render them if present.
4. Conditional rendering to display the error message when it exists and hide the loading spinner when an error occurs.
5. Updating the `isLoading` and `error` states in response to errors or successful data fetching.
6. Live demonstration of the error handling and state management in action.

## Key Manipulations and Scripting/Coding Used
- Adding a catch block to the Fetch operation for handling network errors.
- Simulating network errors by canceling the process from Jason's server using `ctrl C`.
- Checking the response object received from the server for server-sent errors.
- Throwing an error with a custom message when encountering server-sent errors.
- Creating a state variable `const [error, setError]` to store errors.
- Initializing the error state as null: `setError(null)`.
- Conditionally rendering the error message using `{error && <div>{error}</div>}`.
- Updating the `isLoading` and `error` states by setting `isLoading` to false when an error occurs: `setIsLoading(false)`, and clearing the `error` when successful data fetching: `setError(null)`.
- Using the command `npx jason server watch data forward slash db.json at port 8000` to reconnect to the live service.

## Reflective or Quiz-Style Questions
1. Explain how network errors are handled in this tutorial and provide an example of the code used for it.
2. What is the purpose of storing errors in state, and how is it done in this tutorial?
3. Describe the conditional rendering technique used in this tutorial for displaying error messages, and provide an example of its implementation.