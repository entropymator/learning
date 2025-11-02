Full React Tutorial #21 - The React Router (128kbit_AAC-English).mp3
=============================================================

Overview
--------

This study notes focuses on using the React Router to create multiple pages or routes in a React application. By implementing this package, we can reduce server requests and improve site speed and responsiveness compared to traditional multi-page websites.

Main Ideas
----------

1. The React Router is a separate package not included in the core React library, which allows for managing multiple pages or routes in a React application.
2. In contrast to traditional websites that require server requests for each page visit, React applications send initial requests to the server but subsequent page changes are handled by React and the React Router.
3. A top-level component is dynamically injected into the browser for each route or page when a user visits that route.
4. To install the React Router, open a terminal and type `npm install react-router-dom@5` (or specify a different version if needed).
5. Set up routing for your application by importing and using components from the `react-router-dom` package, including BrowserRouter, Route, and Switch. Wrap the entire application with the BrowserRouter component to provide access to routing for all nested components. Place the Switch component inside a content div to display only one route at a time.
6. Create individual routes using the Route component, with each route having a path property specifying the route after the root URL and a nested component to be displayed when that route is visited.

Key Manipulations and Scripting/Coding
----------------------------------------

1. Install the React Router package using `npm install react-router-dom@5` (or specify a different version if needed).
2. Wrap the entire application with the BrowserRouter component to provide access to routing for all nested components.
3. Place the Switch component inside a content div to display only one route at a time.
4. Create individual routes using the Route component, with each route having a path property specifying the route after the root URL and a nested component to be displayed when that route is visited.

Reflective/Quiz-style Questions
-------------------------------

1. What are the main benefits of using the React Router in a React application compared to traditional multi-page websites?
2. Can you explain how the Switch component works within the current setup for managing routes and displaying only one route at a time?
3. How would you set up a new route with a unique path in your React application using the React Router?