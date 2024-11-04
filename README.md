# React-Bootcamp-Toy-Components

Toy Components for a React Crash Course

## Table of Contents
1. [Introduction](#introduction)
2. [Setup Instructions](#Given-setup-instructions)
3. [Installation](#installation)
4. [Additional Project](#additional-project)
5. [Code Exploration Summary](#Code-Exploration-Summary)
6. [Connection with Final Project](#Connection-with-Final-Project)
7. [Reflection](#Reflection)

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


## Connection with Final Project
This bootcamp project provides valuable experience with React, TypeScript, and modular component-based development, all of which are useful for developing complex, scalable front-end applications. While our final project, BlindSight, focuses on creating a local software application to help visually impaired users interact with the file system, the skills gained in this bootcamp can still be highly relevant, especially for any future web-based components that might be incorporated.

### Direct Applications to Future Development:
- **Component-Based Structure**: Building reusable components, as demonstrated in this project, will help streamline development and make it easier to manage a larger codebase. This approach can support any future plans to add a web-based interface for BlindSight, where modularity would enhance scalability and maintenance.

- **TypeScript for Strong Typing**: TypeScript provides static typing, which can help prevent errors, especially in complex applications. This will be advantageous if we decide to create a robust, web-based component for BlindSight, allowing for a more maintainable codebase and reducing potential issues in production.

- **Integration with Vite**: Familiarity with Vite’s fast development server and optimized build process will enhance productivity and provide insights into configuring efficient workflows. If we extend BlindSight to a web-based platform for seamless browser interaction, Vite’s capabilities will be extremely beneficial for development and performance optimization.

While BlindSight currently focuses on a local software solution, these tools and methodologies learned in the bootcamp could be instrumental if we add web-based features to the project, helping to ensure a smooth, accessible, and responsive user experience for web accessing.

## Screenshots
- All screen shots are in the following order:
    - Code 
    - Run command 
    - Output Screen
- **Test vite**:
![testcode](https://github.com/anirudhashastri/React-Bootcamp/blob/e40eda873b8696ae21c73bc3fafb685f2bea479f/Screenshots/test.png)
![testrun](https://github.com/anirudhashastri/React-Bootcamp/blob/e40eda873b8696ae21c73bc3fafb685f2bea479f/Screenshots/test-run.png)
![testweb](https://github.com/anirudhashastri/React-Bootcamp/blob/e40eda873b8696ae21c73bc3fafb685f2bea479f/Screenshots/test-web.png)

- **toycomponents**:
![toycode](https://github.com/anirudhashastri/React-Bootcamp/blob/e40eda873b8696ae21c73bc3fafb685f2bea479f/Screenshots/tocomponents.png)
![toyrun](https://github.com/anirudhashastri/React-Bootcamp/blob/e40eda873b8696ae21c73bc3fafb685f2bea479f/Screenshots/toyscomponents-run.png    )
![toyweb](https://github.com/anirudhashastri/React-Bootcamp/blob/e40eda873b8696ae21c73bc3fafb685f2bea479f/Screenshots/toyscomponemts-web.png)

- **expensetracker**:
![toycode](https://github.com/anirudhashastri/React-Bootcamp/blob/e40eda873b8696ae21c73bc3fafb685f2bea479f/Screenshots/Expenseteacker.png)
![toyrun](https://github.com/anirudhashastri/React-Bootcamp/blob/e40eda873b8696ae21c73bc3fafb685f2bea479f/Screenshots/expensetracker-run.png )
![toyweb](https://github.com/anirudhashastri/React-Bootcamp/blob/e40eda873b8696ae21c73bc3fafb685f2bea479f/Screenshots/expensetracker-web.png)


## Reflection
Working through the toycomponents project has been a pretty rewarding experience. It was cool to see how React and TypeScript work together with Vite, which made development feel fast and smooth. TypeScript was new to me, so it was nice to pick up a bit about it along the way. I especially liked the modular structure, with each component in its own file—it really showed me how a big project could be broken down into manageable pieces.

I’ve worked on some basic websites before, and whenever I needed to see changes during development, I had to manually reload or even restart the instance. Having Vite’s setup, which instantly reflects changes, was super convenient and made things so much easier for development.

One challenge was that the instructions in the README were a bit unclear, with very little guidance provided. Instructions like “clear App.tsx” and “update index.css” left me confused at first; I ended up with a blank screen initially but eventually figured out how to work around it. It also pushed me to explore more and try a test project in the default format, which helped me understand how to set up both the toycomponents project and expensetracker. Overall, this project has been a solid intro to modern front-end development practices, and I’m excited to bring what I’ve learned into my final project.
