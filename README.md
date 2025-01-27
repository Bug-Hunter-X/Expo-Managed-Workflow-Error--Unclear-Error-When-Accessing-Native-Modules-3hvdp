# Expo Managed Workflow Error: Unclear Error When Accessing Native Modules

This repository demonstrates a common issue encountered when using Expo's managed workflow:  unclear errors arising from attempts to access functionalities requiring native modules.  The error messages are often unhelpful, making debugging difficult.

The `expoBug.js` file illustrates the problematic code.  The `expoBugSolution.js` file presents a solution, possibly involving using Expo's supported APIs or ejecting to a bare React Native project.

**Steps to Reproduce:**

1. Clone this repository.
2. Install dependencies: `npm install` or `yarn install`.
3. Run the app using Expo Go or Expo CLI.
4. Observe the error.  The specific error might vary depending on the native module attempted.