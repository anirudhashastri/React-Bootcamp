# React-Bootcamp-Toy-Components

# React-Bootcamp-Toy-Components

Toy Components for a React Crash Course

## Table of Contents
1. [Introduction](#introduction)
2. [Setup Instructions](#Given-setup-instructions)
3. [Installation](#installation)
4. [Additional Project](#additional-project)
5. [Code Exploration Summary](#Code-Exploration-Summary)

## Introduction
This repository contains toy components built as part of a React crash course, providing hands-on practice with React, TypeScript, and essential libraries.

## Given Setup Instructions

Toy Components for a React Crash Course

To set up from scratch:
1 `npm create vite`
2 select `react` and then `typescript`
3 clear `App.tsx`
4 update `index.css`
5 perform the following installation command: `npm i react-hook-form zod react-icons @hookform/resolvers`

Another project, `expensetracker` is also include for reference.

## Additional Project
This repository also includes another project, `expensetracker`, for additional reference and learning.

## Code Exploration Summary
The `toycomponents`, `expensetracker` and `test` (created  by me to just uderstant the set up) project is structured as a TypeScript and React application, using Vite as the build tool. Here’s a breakdown of its key components:

### Main Files:
- **App.tsx**: This is the main component file for the application. It imports several custom components (e.g., `Alert`, `Button`, `RHForm`, `Like`, `ListGroup`, `ExpenseFilter`) and uses `useState` hooks to manage various states like counting clicks, displaying alerts, toggling "like" status, and managing a shopping list. Comments indicate exercises, by having all this it gives a good overall idea how we can usea all these different componets in any project I would like to build in the future.
- **main.tsx**: This file is the entry point of the React application. It renders the `App` component within the root element of `index.html` and applies global styles from `index.css` and `bootstrap.css`.

### Styling:
- **App.css**: Defines specific styling rules for the application’s main elements. It includes styles for centering the main content (`#root`), animations for the logo, and visual effects for interactive elements like buttons and cards.
- **index.css**: Provides basic padding for the `body` element, setting a minimal global style.

### Configuration and Environment:
- **vite-env.d.ts**: Specifies Vite environment types for TypeScript, allowing for better compatibility with Vite's development and build processes.

### Development Setup:
- **Running `npm run dev`**:
   - **Development Server**: Running `npm run dev` starts Vite’s development server, optimized for fast builds and Hot Module Replacement (HMR). This allows code changes to be reflected immediately in the browser without requiring a full page reload.
   - **Local Server**: Vite serves the application locally, typically at `http://localhost:5173`, allowing you to view and interact with the app in a development environment.
   - **File Watching**: Vite continuously watches for any file changes in the project (like updates to `.ts` or `.tsx` files) and automatically reloads the affected modules in the browser, providing a fast feedback loop for smoother development.

The project is modular, with each feature separated into its own component (e.g., `Button`, `Like`). This setup allows for scalability, making it easy to add or modify components as needed.






