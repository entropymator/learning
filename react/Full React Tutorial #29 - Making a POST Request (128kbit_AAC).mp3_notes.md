# Full React Tutorial #29 - Making a POST Request (128kbit_AAC)

This tutorial focuses on making a POST request using the Fetch API in React, specifically to add data to a JSON Server.

## Main Ideas

1. **Creating a POST request**: A fetch request is used instead of console logs to make a POST request to the same endpoint as the GET request for all blogs. The request method is defined as 'POST', and headers specify the content type as application/json. The blog object is converted into a JSON string using `JSON.stringify()`.

2. **Adding a loading state**: A new piece of state, `isPending`, is created and initially set to false. When the form is submitted, `isPending` is set to true, and buttons are managed based on its value to show a loading button while the request is being processed.

3. **Managing blog addition process**: The script checks the status of a pending blog addition, displays an "Adding Blog" message if the status is pending, and redirects users back to the "Add Blog" screen after the blog is added. Conditional statements and redirection are used for managing this process.

## Key Manipulations and Scripting/Coding Used

- Fetch API for making POST requests
- State management (`isPending`)
- `JSON.stringify()` method for converting objects to JSON strings
- Conditional statements and redirection for managing the blog adding process

## Reflective or Quiz-Style Questions

1. What is the primary purpose of using the `isPending` state in this tutorial?
2. How does the script handle the redirect after a successful blog addition?
3. In what way could the loading message be improved or changed for better user experience?