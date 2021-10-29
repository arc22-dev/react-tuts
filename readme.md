![react logo](https://reactjs.org/favicon.ico)

# Getting Started with React App

## Navigation Menu

[About React](#about-react)

- [Declarative](#declarative)
- [Component-Based](#component-based)

[Setup Environment](#setup-environment)

- [Install Editor](#install-editor)
- [Install Node.js](#install-nodejs)

[Create First React App](#create-first-react-app)

- [Run Your First App](#run-your-first-app)
- [Folder Structure](#folder-structure)

---

## About React

A JavaScript library for building user interfaces

### Declarative

React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes.

Declarative views make your code more predictable and easier to debug.

### Component-Based

Build encapsulated components that manage their own state, then compose them to make complex UIs.

Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep state out of the DOM.

[_↑ Go to top_](#getting-started-with-react-app)

---

## Setup Environment

Creating, or setting up the development environment

### Install Editor

We will use [Visual Studio Code](https://code.visualstudio.com/) as a code editor, you can skip this step if you already have installed this or if you use another editor.

- Go to [Visual Studio Code](https://code.visualstudio.com/) downloads page, [click here](https://code.visualstudio.com/download)
- Download preferred installer, stable version
- Open installer and run, complete the setup

### Install [Node.js](https://nodejs.org)

We must have installed [Node.js](https://nodejs.org) for development and package managing.

- Go to [Node.js](https://nodejs.org) downloads page, [click here](https://nodejs.org/en/download/)
- Download the installer file of latest LTS version (.msi for windows)
- Open installer and run, complete the setup

> Now we've done the base setup. Let's [create our first project](#create-first-react-app)

[_↑ Go to top_](#getting-started-with-react-app)

---

## Create First React App

Let's quickly create a react app, following steps

- Open your shell/command prompt/bash in to the directory where you want to create your project
- run command, `npx create-react-app myapp` where _'myapp'_ is the name of your project, it will take some time to be done, wait!
- Open the created folder (myapp) in [Visual Studio Code](https://code.visualstudio.com/)

### Run Your First App

Let's try to run react app by following command in terminal

```
npm start
```

It will open project in browser _(example, localhost:3000)_

### Folder structure

Understanding react app folder structure, files and it's use

- `node_modules` contains node package dependencies, modules for app
- `public` for serving static files, images, scripts, css etc.
- `src` source of the app, contains `App.js` and other source files, all components must be created inside this folder
