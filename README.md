# React Native: Undefined is not an object (evaluating 'this.state.userName' or 'this.props.userName')

This repository demonstrates a common error in React Native applications: attempting to access a state variable or prop before it has been assigned a value.  This often manifests as the error "Undefined is not an object (evaluating 'this.state.userName' or similar)".

The `bug.js` file showcases the problematic code, while `bugSolution.js` provides a corrected implementation.

## Problem

Accessing properties before they are defined results in unexpected behavior, crashes, or blank screens.  This commonly occurs during asynchronous data fetching or improper prop handling.

## Solution

The solution involves conditional rendering or using a default value to prevent accessing undefined properties.  This ensures the application gracefully handles situations where data is not yet available.