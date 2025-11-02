# Full React Tutorial #16 - Using JSON Server

This set of study notes details the process of utilizing JSON Server to manage data in a React application. The primary objective is to learn how to fetch, retrieve, and manipulate data from a JSON server within components.

## Main Ideas

1. Leveraging the `useEffect` hook to fetch data when a component initially renders.
2. Implementing a JSON Server package to create a mock REST API using a JSON file.
3. Creating and structuring a JSON file with blog objects, containing properties like title, body, author, and id.
4. Utilizing `fetch` requests within components to access data from the created API endpoints.
5. Understanding various endpoints for different operations such as fetching, creating, updating, and deleting data.

## Key Manipulations and Scripting/Coding Used

- Create a "data" folder in the project's root directory and generate a new "db.json" file inside it. Populate the JSON file with blog objects.
- Run the `npx json-server --watch data/db.json --port 8000` command to start the JSON server, watching for changes in the JSON file and wrapping it with API endpoints (e.g., `localhost:8000/blogs`).
- Use a `fetch` request within the component to access data from the created API endpoints (e.g., fetching all blogs by sending a GET request to `localhost:8000/blogs`).

## Reflective or Quiz-Style Questions

1. What purpose does the JSON Server package serve in this tutorial, and how is it set up?
2. List the endpoints mentioned in the lecture and describe what each endpoint is used for.
3. How can you fetch all blogs using the `useEffect` hook and the provided API endpoints?