# React Router v6 useParams Hook Issue

This repository demonstrates a common problem and its solution when using the `useParams` hook in React Router v6.  The issue occurs when attempting to access route parameters from a component not directly nested within a route that defines the parameter.  This results in `useParams` returning an empty object initially, leading to errors or unexpected renders.

The `bug.js` file shows the problematic code, while `bugSolution.js` presents a corrected version using `useEffect` to handle the asynchronous resolution of the route parameters.