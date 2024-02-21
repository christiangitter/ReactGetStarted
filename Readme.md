# How to create a React App

## Installation
### Install Node.js
First, ensure that Node.js and npm (Node Package Manager) are installed on your computer. npm comes bundled with Node.js.

### Check Node.js-Installation
Open your terminal (Command Prompt on Windows, Terminal on macOS and Linux) and type the following commands to check if Node.js and npm are installed:


``node -v``
``npm -v``

If these commands return versions, it means both Node.js and npm are successfully installed.

## Create a React Project
You can create a new React project using the Create React App command-line utility. This tool sets up your development environment so you can use the latest JavaScript features, provides a good developer experience, and optimizes your app for production.

1.) Open your terminal and navigate to the directory where you want to create your project.

2.) Run the Create React App command with npx

``npx create-react-app NAME-OF-THE-APP
``
Once the setup is complete, navigate into your project directory:

``cd NAME-OF-THE-APP
``

### Start the Development Server

Inside your project directory, start the development server with:

``npm start
``
This command runs the app in development mode. Open http://localhost:3000 to view it in the browser. The page will automatically reload if you make edits to the code.

## Explore the Project Structure

Take a moment to explore the structure of your new React project. The most important files and directories are:

`public/index.html` - The single HTML file where your React app is rendered.<br>
`src/index.js` - The JavaScript entry point for your React app.<br>
`src/App.js` - A sample React component that serves as the starting point for your app.

## Build Components
React is all about components. Try modifying the src/App.js file to create your first custom component. Here's a simple example:

```
import React from 'react';

function Welcome() {
  return <h1>Hello, React!</h1>;
}

export default Welcome;

```

Replace the default content in App.js with your new component to see the changes in the browser.