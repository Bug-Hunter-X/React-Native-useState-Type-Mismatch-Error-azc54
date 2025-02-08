# React Native useState Type Mismatch Error

This repository demonstrates a common error in React Native applications when using the `useState` hook: type mismatches during state updates.

## Problem
The `useState` hook in React Native expects state updates to maintain type consistency with the initial state value. If you attempt to update the state with a value of a different type, React Native may throw an error, leading to unexpected behavior or crashes.

## Solution
To fix this error, ensure that the type of the value you use to update the state is the same as the initial state type. Use type checking or type guards to prevent this kind of error from occurring in the first place.