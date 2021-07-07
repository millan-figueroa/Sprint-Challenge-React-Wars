# Answers

1.  What is React JS and what problems does it try and solve?
A1: React is a JS library created by FB that makes it faster and easier to create applications using the virtual DOM by re-using components and allowing changes to render automatically thus making a much better user experience.

2.  What does it mean to _think_ in react?
A2: Essentially thinking in React means breaking the application into components and knowing which ones can handle more complex tasks.

3.  Briefly describe some of the differences between a Class/Stateful component and a Functional/Presentational component.
A3: A functional component is basically a plain JS function which accepts props as its argument and returns a react element, it has no state so you can't use 'this.state' inside it, they are simple to read and understand and many components start out as functional.

Class based components is a JS class whose only required method is render(). It provides lifecycle hooks and you can use the this.state property and generally improve component performance.

4.  Describe state.
A4: It is a property that is given by class-based components that determines how the component behaves. 

5.  Describe props.
5A: Props(properties) are the parameters used when creating components. They are how components interact with each other and they flow downwards from the parent component.