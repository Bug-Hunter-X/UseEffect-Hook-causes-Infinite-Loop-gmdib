# React useEffect Infinite Loop Bug
This repository demonstrates a common bug in React applications involving the `useEffect` hook.  The bug occurs when a state variable used inside the `useEffect` function is not included in its dependency array. This leads to an infinite loop because the effect re-runs on every render, causing the state to change, which then triggers another render, and so on.

## How to reproduce
1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.
4. Observe the console output and the application behavior.