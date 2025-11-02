# Full React Tutorial #13 - Functions as Props (128kbit_AAC)

## Overview

This tutorial focuses on utilizing functions as props to manage data within components and demonstrate a delete button for each blog. The delete button triggers a `handleDelete` function that accepts the ID of the blog as an argument, removing the corresponding blog from the list.

## Main Ideas

1. Creating and using a `handleDelete` function in the parent component to remove blogs with specified IDs from the state.
2. Passing functions as props to allow for updating data within other components.
3. Implementing filter method to remove the deleted blog from the list and refresh the page, restoring all data initially loaded.

## Key Manipulations and Scripting/Coding Used

1. Creating a `handleDelete` function inside the parent `Home` component that uses the filter method to remove the blog with the specified ID from the state.
2. Passing the `blogs` state as a prop to child components and using it within the delete button's onClick event to trigger the `handleDelete` function.
3. Setting the new filtered array (`newBlogs`) as the new value of the `blogs` state, causing the deleted blog to be removed from the list.

## Reflective or Quiz-Style Questions

1. How does passing functions as props allow for updating data within other components?
2. What method is used to remove a specific blog from the list based on its ID?
3. Explain how refreshing the page restores all data in this context.