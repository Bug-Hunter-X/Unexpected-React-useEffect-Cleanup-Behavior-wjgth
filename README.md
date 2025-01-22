# Unexpected React useEffect Cleanup Behavior

This repository demonstrates a common React bug where the cleanup function in `useEffect` is not called as expected when the component unmounts.

The `bug.js` file contains the buggy code.  The `bugSolution.js` file provides the corrected version. The issue arises from incorrect usage of the useEffect hook's dependency array leading to unexpected behavior and potential memory leaks.