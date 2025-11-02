# Full React Tutorial #18 - Conditional Loading Message (128kbit_AAC-English)

## Overview
In this tutorial, we'll learn how to create a loading message while data is being fetched in a React application. This will help improve the user experience by providing feedback during the delay between requesting and receiving data.

## Main Ideas
1. Create an additional state called `isPending` or `isLoading` using React's `useState`.
2. Utilize a conditional template to display the loading message only when `isPending` is true.
3. Wrap the fetch function with a `setTimeout` function to simulate a delay in data fetching.
4. Hide the loading message once data has been received by setting `isPending` to false.
5. Be aware of the impact of using a deliberate delay in real-world applications, as it can slow down response times.

## Key Manipulations and Scripting/Coding Used
1. Using React's `useState` hook to manage additional state for loading indicators.
2. Conditional rendering with JavaScript to display the loading message when appropriate.
3. Wrapping the fetch function inside a `setTimeout` function to create a simulated delay in data fetching.
4. Updating the state of `isPending` to true or false depending on whether the data is being fetched or has been received.

## Reflective or Quiz-Style Questions
1. What purpose does the `isPending` state serve in this tutorial?
2. How can you improve the user experience further by expanding upon conditional loading messages?
3. Can you think of a real-world application scenario where a delay in data fetching is acceptable and beneficial for UX reasons?