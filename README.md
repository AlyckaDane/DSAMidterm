# <h2>What is React.js?</h2>

React is a free and open-source front-end JavaScript toolkit for creating user interfaces based on Facebook Inc. components. It is also referred to as React.js or ReactJS. Meta (previously Facebook) and a group of independent developers and businesses are in charge of maintaining it.

With frameworks like Next.js, React may be used to create server-rendered, mobile, or single-page applications. React applications frequently rely on libraries for routing and other client-side functionality because React is only concerned with the user interface and rendering components to the DOM. One of React's main advantages is that it only re-renders the parts of the page that have changed, avoiding needless re-rendering of unchanged DOM elements. The initial launch date was May 29, 2013.

# <h3>Notable Features</h3>
React follows the declarative programming approach. React updates and displays components in response to data changes, and developers create views for every state of an application. On the other hand, imperative programming is different.

<h4>Declarative</h4>
React follows the declarative programming approach, with developers creating views for each application state and React updating and rendering components as data changes This contrasts with imperative programming.

<h4>Components</h4>
React code consists of modular and reusable components. React applications often include multiple levels of components. The components are rendered to a root element in the DOM via the React DOM framework. When rendering a component, values are exchanged across components using props (short for "properties"). A component's internal values are referred to as its state.

React has two major ways of declaring components: function components and class components.

<h4>Function Components</h4>
Function components are defined as functions (using JavaScript function syntax or an arrow function expression) that take a single "props" parameter and return JSX. From React v16.8, function components can use state using the useState Hook.

<h4>React Hooks</h4>
On February 16, 2019, React 16.8 was released to the public, introducing React Hooks. Hooks are functions that let developers "hook into" React state and lifecycle features from function components. Hooks do not work inside classes — they allow developers to use more React features without classes.


React provides several built-in hooks such as [useState], [useContext],  [useReducer], [useMemo] and [useEffect]. Others are documented in the Hooks API Reference.  [useState] and [useEffect], which are the most commonly used, are for controlling state and side effects, respectively.

<h5>Rules of hooks</h5>

The distinctive code patterns that hooks rely on are described by the following two hook rules:

1. To ensure that the hooks are called in the same sequence every time, "Only call hooks at the top level" means that you should not call hooks from inside loops, conditions, or nested expressions.

2. To ensure that stateful logic remains with the component, "Only call hooks from React functions" should be used instead of using hooks from standard JavaScript methods.

Code analysis tools like linters can be set up to identify several errors during development, even though these guidelines cannot be enforced at runtime. Both using Hooks and implementing bespoke Hooks that may call other Hooks are subject to the regulations.


# <h2>Setting up a React.js</h2>
### Prerequisite Apps

Before installing React JS, you need to have the following software installed on your system:

- **Node.js**: React relies on Node.js for package management (NPM/Yarn). You can download it from [Node.js official website](https://nodejs.org/).

- **Code Editor**: A good code editor like [Visual Studio Code](https://code.visualstudio.com/) is recommended for React development.

# <h2>Why is it Useful?</h2>

An open-source JavaScript package called React facilitates the creation of dynamic user interfaces (UIs). It can be used to create components that stand in for logically reusable UI elements.

Anyone can view, examine, alter, and improve React's source code to suit their own demands or app development specifications because it is open source.


# <h2>How to Install React - A Step-by-step Guide</h2>

<h3>Step: 1 Install Node.js</h3>

- You must have Node.js installed on your computer before you can install React. A JavaScript runtime environment called Node.js enables server-side JavaScript execution. The most recent stable version, which incorporates security upgrades, bug fixes, and compliance with project dependencies, is the one that is advised. To download the suggested or most recent version, go to the Node.js website. 

Download and install your preferred Node version on your computer. Confirm installation by typing node -v in the command prompt, which should display the current version.

<h3>Step 2: Verify NodeJS Installation</h3>
- Open the command prompt to check whether it is completely installed or not type the command –> [node -v]. If the installation went well it will give you the version you have installed  

<h3> Step 3: Install the CRA ackage</h3>
- Now in the terminal run the below command to install create-react-app: [npm install -g create-react-app]   It will globally install react app for you. To check everything  went well run the command [create-react-app --version] If everything went well it will give you the installed version of react app

<h3>Step 4: Create Directory for React Projects</h3>

- Now Create a new folder where you want to make your react app using the below command: [mkdir newfolder] **Note**: The newfolder in the above command is the name of the folder and can be anything.

- Move inside the same folder using the below command: [cd newfolder (your folder name)]

<h3>Step 5: Create the React App using CRA Command</h3>
- Now inside the folder run the command –> [npx create-react-app reactfirst] It will take some time to install the required dependencies

- **NOTE**: Due to npm naming restrictions, names can no longer contain capital letters, thus type your app’s name in lowercase.

<h3>Step 6: Open the Project in Code editor</h3>
- Now open the IDE of your choice for eg.  Visual studio code and open the folder where you have installed the react app newfolder (in the above example)  inside the folder you will see your app’s name reactapp (In our example). Use the terminal and move inside your app name folder.Use command  cd reactapp (your app name)

<h3>Step 7: Run the React App</h3>
- To start your app run the below command : [npm start] Once you run the above command a new tab will open in your browser showing React logo


