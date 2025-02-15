# Unexpected State Updates in React's useState Hook
This repository demonstrates a common issue in React applications related to the useState hook.  When you update state multiple times within a single function call, only the last update is reflected. This can lead to missed updates and unexpected behavior. 
The `bug.js` file contains the problematic code, while `bugSolution.js` offers a solution.
## Issue
The issue arises when calling `setCount` multiple times in rapid succession in the `handleClick` function.
## Solution
The solution utilizes the functional update style of useState for predictable state updates.