# React Info

## What is React?
React is an open-source frontend JavaScript library which is used for building user interfaces especially for single page applications. It is used for handling view layer for web and mobile apps. 

## What are the major features of React?
It uses VirtualDOM instead of RealDOM considering that RealDOM manipulations are expensive.
Supports server-side rendering.
Follows Unidirectional data flow or data binding.
Uses reusable/composable UI components to develop the view.

## What is Virtual DOM?
The Virtual DOM (VDOM) is an in-memory representation of Real DOM. The representation of a UI is kept in memory and synced with the "real" DOM. It's a step that happens between the render function being called and the displaying of elements on the screen. This entire process is called reconciliation.

The Virtual DOM works in three simple steps.

1. Whenever any underlying data changes, the entire UI is re-rendered in Virtual DOM representation.

2. Then the difference between the previous DOM representation and the new one is calculated.

3. Once the calculations are done, the real DOM will be updated with only the things that have actually changed.

## What is JSX?
provides syntactic sugar for the React.createElement() function, giving us expressiveness of JavaScript along with HTML like template syntax.

## How to create components in React?
Function Components: This is the simplest way to create a component. Those are pure JavaScript functions that accept props object as first parameter and return React elements:

Class Components: You can also use ES6 class to define a component.

## What is state in React?
State of a component is an object that holds some information that may change over the lifetime of the component.

## What are props in React?
Props are inputs to components, They are data passed down from a parent component to a child component.

## What is "key" prop and what is the benefit of using it in arrays of elements?
A key is a special string attribute you should include when creating arrays of elements. Key prop helps React identify which items have changed, are added, or are removed.

## What are controlled components?
A component that controls the input elements within the forms on subsequent user input is called Controlled Component, i.e, every state mutation will have an associated handler function.

## What are uncontrolled components?
The Uncontrolled Components are the ones that store their own state internally, and you query the DOM using a ref to find its current value when you need it. This is a bit more like traditional HTML.

## What are Higher-Order Components?
A higher-order component (HOC) is a function that takes a component and returns a new component. Basically, it's a pattern that is derived from React's compositional nature.

## What is context?
Context provides a way to pass data through the component tree without having to pass props down manually at every level.

## What is children prop?
Children is a prop (this.props.children) that allow you to pass components as data to other components, just like any other prop you use. Component tree put between component's opening and closing tag will be passed to that component as children prop.

## Why React uses className over class attribute?
class is a keyword in JavaScript, and JSX is an extension of JavaScript. That's the principal reason why React uses className instead of class. Pass a string as the className prop.

## What are Hooks? 
Hooks are functions that let us “hook into” React state and lifecycle features from a functional component.React Hooks cannot be used in class components. They let us write components without class.

## What are the different ways to style a React component?
1. Inline Styling
We can directly style an element using inline style attributes.

2. Using JavaScript object
We can create a separate JavaScript object and set the desired style properties.

3. CSS Stylesheet
We can create a separate CSS file and write all the styles for the component inside that file. This file needs to be imported inside the component file.

4. CSS Modules
We can create a separate CSS module and import this module inside our component. Create a file with “.module.css”‘ extension,
styles.module.css:

## Name a few techniques to optimize React app performance.
>Using useMemo( ) -
It is a React hook that is used for caching CPU-Expensive functions.

>Using React.PureComponent -
It is a base component class that checks state and props of a component to know whether the component should be updated.
Instead of using the simple React.Component, we can use React.PureComponent to reduce the re-renders of a component unnecessarily.

>Lazy Loading -
It is a technique used to reduce the load time of a React app. Lazy loading helps reduce the risk of web app performances to minimal.