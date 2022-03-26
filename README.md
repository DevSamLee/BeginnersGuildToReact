# BeginnersGuildToReact
> This repo contains source code from 'A Beginners Guide to React Introduction'
>
> Link: https://egghead.io/lessons/react-a-beginners-guide-to-react-introduction

## Learning takeaways

### 01-document-create-element.html
* Get element by using `getElementById`
* Create element by using `createElement`
* Add text content to the element by using `textContent`
* Add class name to the element by using `className`
* Add child element by using `appendChild()`

### 02-react-create-element.html
* Create element by using `React.createElement()`
* Add children element by using `children: React.createElement()`
* Declare element class name by using `className:`
* Create relationship by using `ReactDOM.render(element, rootElement)`

### 03-jsx.html
* Create element by using babel stand alone (similar syntax with html)

### 04-jsx-tricks.html
* Create property of element by using `{…props}`
* Override property of element by adding declaration

### 05-fragments.html
* Add two variables to `ReactDOM.render()` by using `<React.Fragment></React.Fragment>` or `<></>`

### 06-custom-component.html
* How to use arrow function `() => {}` for custom component
* To use `<message>` tag as a function, it must start with Uppercase (message -> Message)
* If not, complier understands `<message>` tag as a string and then creates as a DOM
* Compare to `<div>` and `<Message>` tags at console log
  
### 07-prop-types.html
* Add prop-types.js in script to use propTypes function
* Check validation of component by using condition: `string(props, propName, componentName)`
* Check validation of every component by using `PropTypes.string.isRequired` to each component

### 08-jsx-interpolation.html
* Add js function with jsx by using `<>` and go back to js by using `{}`

### 09-re-render.html
* Re-rendering application without delating the focus by using jsx in React

### 10-styling.html
* Add style to each element by using function with `…rest` and `…style` to minimize duplication of code
* Use style function in js, it should be declared as `CamelCase` not as `KebabCase` (e.g back-ground Color => backgoundColor)

### 11-event-handlers.html
* Add `setState` and `renderApp` function for updating state and re-render the app
* `onCount ={() => setState({username:''})}` to set the function in the tag
* Or make as a function `handleChange` outside of the jsx

### 12-state.html
* Create link between label and input by using `htmlFor` in jsx
* Use state in a React function component by using `React.useState()` with any type of variable

### 13-side-effects.html
* Use `React.useEffect` to set the value in local storage
* Use `window.localStorage.getItem` to initialize it

### 14-lazy-initialization.html
* Use `() => {}` is called as `lazy initializer` to avoid unnecessary retrieving

### 15-effect-deps.html
* Use dependency array to syncronize state of application
* Call back function relys on dependency array

### 16-custom-hooks.html
* Create a function by generalization
* Change the names of variables or parameters
* Call it in other function 
