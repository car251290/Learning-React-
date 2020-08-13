# Learning-React-
How to start a react app

# React App

React has been designed from the start for gradual adoption, and you can use as little or as much React as you need. 
Whether you want to get a taste of React, add some interactivity to a simple HTML page, or start a complex
React-powered app, the links in this section will help you get started.

# JavaScript Resources
The React documentation assumes some familiarity with programming in the JavaScript language. 
You don’t have to be an expert, but it’s harder to learn both React and JavaScript at the same time.

# Start in React-app
Create React App doesn’t handle backend logic or databases; it just creates a frontend build pipeline, so you can use it with any backend you want. Under the hood, it uses Babel and webpack, but you don’t need to know anything about them.
When you’re ready to deploy to production, running npm run build will create an optimized build of your app in the build folder. You can learn more about Create React App


A JavaScript build toolchain typically consists of:
A package manager, such as Yarn or npm. It lets you take advantage of a vast ecosystem of third-party packages, and easily install or update them.
A bundler, such as webpack or Parcel. It lets you write modular code and bundle it together into small packages to optimize load time.
A compiler such as Babel. It lets you write modern JavaScript code that still works in older browsers.
If you prefer to set up your own JavaScript toolchain from scratch, check out this guide that re-creates some of the Create React App functionality.

## Hooks
But what is a Hook?
Hooks are functions that let you “hook into” React state and lifecycle features from function components. Hooks don’t work inside classes — they let you use React without classes. (We don’t recommend rewriting your existing components overnight but you can start using Hooks in the new ones if you’d like.)

## Rules for Hooks

Hooks are JavaScript functions, but they impose two additional rules:
Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions. (There is just one other valid place to call Hooks — your own custom Hooks. We’ll learn about them in a moment.)
We provide a linter plugin to enforce these rules automatically. We understand these rules might seem limiting or confusing at first, but they are essential to making Hooks work well.

