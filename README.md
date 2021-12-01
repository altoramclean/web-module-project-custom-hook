# Composing Stateful Logic - Dark Mode

This project allows you to practice the concepts and techniques learned in this module and apply them in a concrete project. This module explored Form management in React. You learned what stateful logic is, how to build custom hooks, and how to compose multiple hooks together. In your project you will demonstrate proficiency of these subjects and principles by creating an application using each of these.


## Objectives
- Build custom hooks that extend stateful logic
- Build custom hooks that work with persistent data
- Compose hooks together

## Introduction
In this project you'll take this crypto currency tracker app and build two custom hooks that, when composed together, will allow users to set and persist a dark mode preference.

***Make sure to complete your tasks one at a time and complete test each task before proceding forward.***

## Instructions
### Task 1: Project Set Up
* [x] Create a forked copy of this project.
* [x] Clone your OWN version of the repository in your terminal
* [x] cd into the project base directory `cd web-module-project-custom-hook`
* [x] Download project dependencies by running `npm install`
* [x] Start up the app using `npm start`

### Task 2: Project Requirements
#### Build a useDarkMode hook
* [x] Create a new folder called `hooks.`
* [x] Create a file called `useDarkMode.js`.
* [x] Build a hook that ONLY setups a boolean state value. This value governs if dark mode is on or off.
* [x] Return the slice of state created and the state modification function.
* [x] Replace the darkMode state definition with useDarkMode in index.js.

#### Build a useLocalStorage hook
* [x] Create a file called `useLocalStorage.js`.
* [x] Build a hook called that takes in a key value and an initialValue.
* [x] Use the code from GP to build the the hook.

#### Compose useLocalStorage around useDarkMode
* [x] Import useLocalStorage into the useDarkMode hook.
* [x] Confirm that when clicking the dark mode switch on the ui that the correct value is saved to localStorage.
* [x] Confirm that dark mode persists when reloading the app.



## Submission Format
- [x] If this is your first time connecting a submission, authorize your github account within the codegrade assignment.
- [x] Connect your fork to Codegrade using the "Connect Git" button.
- [x] Find your newly created fork from the list and push your work to main.
- [x] Check this video for details: www.youtube.com/watch?v=fC2BO7dI6IQ
