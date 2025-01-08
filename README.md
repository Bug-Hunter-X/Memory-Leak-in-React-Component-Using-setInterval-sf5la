# React setInterval Memory Leak

This repository demonstrates a common mistake when using the `setInterval` function within a React component's `useEffect` hook.  The provided code causes a memory leak because it does not return a cleanup function to stop the interval when the component unmounts.

The `bug.js` file showcases the faulty code, resulting in a memory leak. The `bugSolution.js` file provides the corrected version.