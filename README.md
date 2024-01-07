# My-notes

## React
useEffect is run after browser has repainted.

useLayoutEffect is run before paint and after DOM has rendered

A higher-order component in Reactjs is a function that takes a component and returns a new component with additional props. It's a technique that allows you to reuse logic across multiple components.

useRef is used to declare a variable where the value should not change even when the component is rerendered. \
Also it is used to reference a DOM element.

forwardRef is used when you need to pass a ref to the child and access and modify its property (bcz passing refs like a prop won't work.)

useImperativeHandle is used when you need to call a function or anything of children from its parent.

## Frontent JS
Bubbling means event is propogating up the DOM tree (child to parent).

Tricking or capturing means event is propogating down the DOM tree (parent to child).

## JS
Higher order function are functions which takes function as parameters or returns a function. Ex: filter, map, reduce etc.
