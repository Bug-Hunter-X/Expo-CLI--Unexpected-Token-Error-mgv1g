# Expo CLI Unexpected Token Error

This repository demonstrates a common error encountered when using the Expo CLI, specifically an unexpected token error.  This error usually stems from issues with project configuration, version mismatches, or corrupted cache.

The `expoBug.js` file showcases a project with a problematic configuration or code that triggers the error. The `expoBugSolution.js` offers solutions to resolve this issue.

**Steps to Reproduce:**

1. Clone this repository.
2. Navigate to the project directory.
3. Attempt to run `expo start` (or other relevant Expo CLI commands).
4. Observe the unexpected token error.

**Solutions (see expoBugSolution.js):**

* Check Expo CLI and project dependencies for version mismatches.
* Clean and rebuild your project.
* Examine App.json, package.json, and other configuration files for errors.
* Verify your code for syntax errors or incompatible language features.