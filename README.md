# React Native FlatList Empty List Bug

This repository demonstrates a common bug in React Native where a FlatList component renders an empty list even after a successful API call. The issue is caused by incorrect data handling within the component's lifecycle methods.  This example shows the bug and the solution.

## Bug

The `bug.js` file contains the buggy component.  The API call successfully fetches data, but the FlatList remains empty. This is likely due to an issue with the `useState` hook or asynchronous data updates. 

## Solution

The `bugSolution.js` file provides a corrected version of the component.  The solution addresses the asynchronous nature of data fetching and ensures that the FlatList updates correctly after the data is received.

## Setup

1. Clone the repository
2. Navigate to the project directory
3. Run `npm install` or `yarn install`
4. Run the app using your preferred React Native development environment.