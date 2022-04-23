# CI & CD example

## About
This project provides an implementation of a CI workflow such that:

- Using Git hooks, runs all tests before every commit.
- Using Git hooks, runs Eslint over all the .js and .jsx files in the src/ folder before every commit.
- Using Github actions, runs all tests and Eslint every time a push is executed.
 
and a CD workflow that:

- Deploys a production version of our app whenever a push is made in the main branch.

Furthermore, a protection rule has been set up so that:

- Direct commits to the main branch are not allowed.
- The status checks must pass to execute a merge to main.

## Demo
Following this link you can visit [the deployed app](https://magiudev-personal-projects.github.io/ci-cd-example/)
