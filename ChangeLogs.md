## Overview
Summary of changes made in the pull request for the **Quiz App** project.

## Changes Made

### Branch Updates
- Renamed the default branch from `master` to `main`.
- Created a new branch `dev` for feature development.

### File Modifications

#### `src/App.jsx`
- Removed the default React boilerplate code.
- Integrated a new `WelcomePage` component.

#### `src/components/WelcomePage.jsx`
- Created the `WelcomePage` component with the following content:
  ```jsx
  <div className="text-blue-700 font-extrabold text-xl"> 
      This is the Welcome Page of Eugene Kpakpo Acquaye's ALX Capstone Quiz
  </div>

  <h1 className="text-slate-400 font-serif font-semibold">Vite + React</h1>
  ```
- Used Tailwind CSS for styling and exported the component for reuse.

## Impact of Changes
- Replaced default content with a personalized welcome page.
- Enhanced the UI with Tailwind CSS for modern styling.
- Established a modular structure for future development.
