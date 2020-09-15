# Props and State

__Does a deployed React application require a server?__  
You do not need a server with a deployed React application.  
https://create-react-app.dev/docs/deployment/#:~:text=You%20don't%20necessarily%20need,an%20existing%20server%20side%20app.  
__Why do we prefer to test a React application at the behavior rather than the unit level?__  
This is important because of what we are doing with React. We need to know that it is behaving correctly to know that is is working, and we can do this with react-testing-library.  
https://medium.com/@jylglim/enzyme-vs-react-testing-library-a-tdd-bdd-comparison-with-examples-7b9f0b380a48  
__What does `npm run build` do?__   
This command creates a build directory with a production build of the app.  
https://create-react-app.dev/docs/deployment/  
__Describe the actual composition/architecture of a React application__  
There is a compenent hierarchy in a React app. Each component should match one piece of dat ain the application. Data flows down the component hierarchy.  
https://reactjs.org/docs/thinking-in-react.html    

### Vocabulary
|Term | Definition |  
|---|---|
| BDD | Stands for behavioral driven development. We run tests with React that will work with DOM nodes and find buttons, links, and text to make sure the page is behaving properly. https://medium.com/@jylglim/enzyme-vs-react-testing-library-a-tdd-bdd-comparison-with-examples-7b9f0b380a48| 
| Acceptance Terms | This is a type of testing that tests an application for acceptability. The goal is to make sure that the application meets all the requirements. https://www.geeksforgeeks.org/acceptance-testing-software-testing/ |
| mounting | This means putting elements in the DOM. The built in methods called are `constructor()`, `getDerivedStateFromProps()`, `render()`, and `componentDidMount()`  https://www.w3schools.com/react/react_lifecycle.asp  | 
| build | React apps are built. Writing a react app is called building. https://reactjs.org/|


### Links: 
[Roles Reference](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques#Roles)