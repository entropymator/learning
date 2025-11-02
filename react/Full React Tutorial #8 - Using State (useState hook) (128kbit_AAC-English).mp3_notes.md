# Full React Tutorial #8 - Using State (useState hook)

**Overview:**
This tutorial discusses the concept of component state in React, focusing on using the useState hook to manage and update state within functional components.

## Main Ideas
1. Component state refers to data used within a component at a specific point in time, which can be an array, boolean, string, object, or any other form.
2. When attempting to update a variable in response to a user event, such as clicking a button, the useState hook is introduced as a solution.
3. To use `useState`, you must import it from the React library at the top of the file, create a state variable with an initial value, and destructure the returned values (initial state and a function to update the state) into separate variables.
4. In the template, the state variable can be used to display the current value, and the update function can be called to change the state value when needed.
5. The data type of the state does not matter and can be manipulated using the `setXxx` function.
6. Multiple instances of `useState` can be used within a single component for different values.

## Key Manipulations and Scripting/Coding Used
1. Import useState from React library at the top of the file: `import React, { useState } from 'react';`
2. Create a state variable with an initial value: `const [mario, setMario] = useState('Super Mario');`
3. Use the state variable to display the current value in the template: `<h1>{mario}</h1>`
4. Call the update function (`setMario`) to change the state value when needed: `<button onClick={() => setMario('Yoshi')}>Change Character</button>`

## Reflective or Quiz-Style Questions
1. How does the useState hook help manage and update component state in React?
2. What is the process for using the useState hook to create a reactive value within a functional component?
3. Can you explain how changes to a state value trigger a re-render of the component, updating the displayed value in the template?