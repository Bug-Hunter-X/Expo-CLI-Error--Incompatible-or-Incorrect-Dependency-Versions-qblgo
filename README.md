# Expo CLI Error: Incompatible or Incorrect Dependency Versions

This repository demonstrates a common error encountered when using the Expo CLI: issues arising from incorrect or incompatible dependency versions specified in the `package.json` file.

The `bug.js` file shows an example of a project with a problematic dependency version. The `bugSolution.js` file presents the corrected version.

## Steps to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Attempt to start the Expo development server using `expo start`.
4. Observe the error messages (if any).
5. Review the `bugSolution.js` for the correction.

## Solution

Carefully review your `package.json` file's dependencies. Ensure that all versions are compatible with each other and with the Expo SDK version you're using. Consider using a version manager (like npm or yarn) to manage your project's dependencies and their versions.  Using a package manager's lockfile is also recommended to ensure consistent builds across environments.