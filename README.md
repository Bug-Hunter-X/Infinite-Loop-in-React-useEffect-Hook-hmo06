# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook.  The bug causes an infinite rendering loop due to an incorrectly specified dependency array.

## Bug Description

The `useEffect` hook is used to perform side effects after a component renders.  However, if the dependency array is missing or incorrect, the effect can trigger repeatedly, leading to an infinite loop and crashing the application.

## How to Reproduce

Clone this repository and run `npm start` to start the development server.  You'll observe the console logging "Count" continuously and the application will be unresponsive.