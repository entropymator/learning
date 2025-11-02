# Full React Tutorial #12 - Reusing Components

In this tutorial, we focus on the importance of making our code more reusable by separating components and demonstrating this with the `BlogList` component.

## Main Ideas

1. **Component Separation**: The logic for displaying data was moved from a parent (Home) component to a separate child (BlogList) component, making the code more modular and reusable across different parts of the application.
2. **Filtering Data**: To filter and display only specific blogs (in this case, Mario's blogs), the `BlogList` component uses the `filter` method on the `blogs` array it receives as a prop.
3. **Condition Check**: The `filter` method loops through each item in the `blogs` array and returns `true` or `false`, which determines whether an item is included or excluded from the final result. To filter only Mario's blogs, a condition check is performed on the `author` property of each blog to ensure it equals "mario".
4. **Dynamic Display**: The filtered `blogs` array is then passed as a new prop into the component, allowing for different data to be displayed based on the given prop. This demonstrates the reusability and versatility of the BlogList component.

## Key Manipulations/Scripting

1. Extracting the `BlogList` component from the parent Home component.
2. Implementing a filter function in the `BlogList` component using the JavaScript `filter()` method.
3. Checking the author property of each blog to determine whether it is one of Mario's blogs.
4. Passing the filtered `blogs` array as a new prop into the `BlogList` component for dynamic display.

## Reflective Questions

1. Why is it important to separate components in a React application? Provide examples.
2. What methods can you use to filter data in JavaScript, and when would you choose each one?
3. Can you think of another scenario where reusing a component might be beneficial in a React project? Describe the component and the situation.