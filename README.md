# React useEffect Infinite Loop Bug

This repository demonstrates a common React bug involving the `useEffect` hook and missing dependencies.  The `setInterval` function keeps creating new intervals every render, leading to an uncontrolled increase in the number of intervals running, and potentially causing performance issues or crashes.