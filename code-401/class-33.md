# Context API

__Describe use cases for `useMemo()` and `useReducer()`__  
`useReducer()` is useful when you need to use complex state logic, when you have mulitple sub values, or when the next state depends on the previous state.  Use `useMemo()` runs during rendering, and it will only recompute the memoized value when one of its dependants has changed. This is an optimized way to avoid calculations every rerender.  
https://reactjs.org/docs/hooks-reference.html  
  
__Why do custom hooks need the use prefix?__   
It needs the prefix so that looking at it, you can immediately tell that it is a hook. Without this, it looks just like a regular function.  
https://reactjs.org/docs/hooks-custom.html  

__What do custom hooks usually do?__   
They give functionality that can be used across multiple components, and they are better than functions because they can access state and component lifecycle.  
https://dev.to/wellpaidgeek/how-to-write-custom-hooks-in-react-1ana#:~:text=Custom%20hooks%20allow%20you%20to,like%20component%20lifecycle%20and%20state.  
__Using any list of custom hooks, research and name one that you think will be useful in your applications__   
react-use-form-state is a hook that helps maintain the state in different parts of an app. This could be really useful, as this has been a challenge in the ToDo app.  
https://blog.bitsrc.io/10-react-custom-hooks-you-should-have-in-your-toolbox-aa27d3f5564d  
__Describe how a hook that fetches API data might work__  
An API fetching hook would take in a url and any info necessary for the request and return the results of the API call. It could use a callback to update the state with the returned results.  


|Term | Definition |  
|---|---|
| reducer |  This is a function that determines the changes to an application's state, using the action that it receives.  https://css-tricks.com/understanding-how-reducers-are-used-in-redux/|
