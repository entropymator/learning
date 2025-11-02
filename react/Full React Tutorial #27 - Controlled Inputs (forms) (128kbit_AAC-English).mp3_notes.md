Full React Tutorial #27 - Controlled Inputs (forms)
==================================================

Overview
--------

In this tutorial, we delve into controlled inputs in React, a method to manage user input forms and maintain synchronization between the input field values and component state. We'll create a blog form with text fields for title and body, an author select field, and an add-blog button.

Main Ideas
----------
1. Create a "create" component for our blog form.
2. Design each field with specific attributes like type, required, label, etc.
3. Add styles to enhance the form's presentation.
4. Track user inputs in React components by using state variables and associating them with input values.
5. Utilize the `onChange` event to update states when users type or select options.
6. Display current state values for feedback.
7. Implement a select field and manage selected value using the "author" state variable.
8. Demonstrate form submission in upcoming sections.

Key Manipulations & Scripting
------------------------------
- Create state variables (e.g., `const [title, setTitle] = useState('')`) for each text input field and an author select field.
- Associate states with input values using attributes such as `value={title}`.
- Implement the `onChange` event to update state values upon user interaction: `onChange={() => setTitle(event.target.value)}`.
- Display the current state values at the bottom for feedback: `<p>{title}</p>`.
- Set an initial author value (e.g., "Mario") and use an 'onChange' event to update the "author" state variable with the new selected value.

Reflective or Quiz-style Questions
----------------------------------
1. How do we associate states with input values in a React component?
2. What is the purpose of using the `onChange` event in controlled inputs?
3. Explain how we can demonstrate that the form's state is being tracked and updated correctly when users interact with the form.