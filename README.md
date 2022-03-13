# BeginnersGuildToReact
> This repo contains source code from 'A Beginners Guide to React Introduction'
>
> Link: https://egghead.io/lessons/react-a-beginners-guide-to-react-introduction

## Learning takeaways

### 01.
* Get element by using ‘getElementById’
* Create element by using ‘createElement’
* Add text content to the element by using ‘textContent’
* Add class name to the element by using ‘className’
* Add child element by using ‘appendChild()’

### 02.
* Create element by using ‘React.createElement()’
* Add children element by using ‘children: React.createElement()’
* Declare element class name by using ‘className:’
* Create relationship by using ‘ReactDOM.render(element, rootElement)’

### 03.
* Create element by using babel stand alone (similar syntax with html)

### 04.
* Create property of element by using {…props}
* Override property of element by adding declaration

### 05.
* Add two variables to ReactDOM.render() by using <React.Fragment></React.Fragment> or <></>

### 06.
* How to use arrow function () => {} for custom component
* To use <message> tag as a function, it must start with Uppercase (message -> Message)
* If not, complier understands <message> tag as a string and then creates as a DOM
* Compare to '<div>' and '<Message>' tags at console log
  
### 07.
* Add prop-types.js in script to use propTypes function
* Check validation of component by using condition: string(props, propName, componentName)
* Check validation of every component by using ‘PropTypes.string.isRequired’ to each component

### 08.
* Add js function with jsx by using <> and go back to js by using {}
