# RCT101-day-1

What is React and why use it?
The React.js framework is an open-source JavaScript framework and library developed by Facebook. It's used for building interactive user interfaces and web applications quickly and efficiently with significantly less code than you would with vanilla JavaScript.

Who made React?
ans- Facebook 

what is Babel?
Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments.

How does Babel convert html code in React into valid code?
Babel converts HTML code into valid code by using the JSX code and converter. A user can essentially use future JavaScript in the browsers of today thanks to Babel, a very well-known transpiler.


What is ReactDOM used for? Write an example?
ReactDOM is a module in React that provides methods for rendering React elements into the DOM (Document Object Model). It is used for creating and rendering React components in web applications.

What are the packages that you need to import for react to work with?
To use React in your application, you need to import two packages: react and react-dom

What is React.createElement?
React. createElement( type, [props], [... children] ) Create and return a new React element of the given type. The type argument can be either a tag name string (such as 'div' or 'span' ), a React component type (a class or a function), or a React fragment type.

What are the three properties that createElement accept?
type : The type you have passed.
props : The props you have passed except for ref and key . ...
ref : The ref you have passed. ...
key : The key you have passed, coerced to a string.


What is the meaning of render and root?
In React, "render" refers to the process of converting a React component or element into a form that can be displayed on the screen. The ReactDOM.render() method is used to render a React element or component to a target DOM node.
In React, "root" typically refers to the top-level DOM node where your React application is mounted. This is the node that you specify as the second argument to ReactDOM.render(). When you render a React component or element to a root node, React will create a virtual DOM representation of the component or element and update the actual DOM to match it.
