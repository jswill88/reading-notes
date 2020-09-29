# Redux - Combined Reducers

__Why choose Redux instead of the Context API for global state?__  
Redux is the industry standard for managing state of large applications, so it is important to know well. It is more optimized for larger projects, because the context API rerenders more often.  
https://dev.to/ibrahima92/redux-vs-react-context-which-one-should-you-choose-2hhh#redux-vs-the-react-context-who-wins  
__What is the purpose of a reducer?__  
We need reducers to tell the application how to change state in response to an action. The action does not do anything except describe what happended and it is up to the reducer to respond to this.  
https://redux.js.org/basics/reducers  
__What does an action contain?__  
An action contains a type and whatever payload you want it to have. There is flexibility in what there is besides the type.  
https://redux.js.org/basics/actions  
__Why do we need to copy the state in a reducer?__  
The reducer needs to be a pure function without any side-effects. It should only take in an action and return the new state, but it should not mutate the state, so we need to copy it to update it.  
https://redux.js.org/basics/reducers  

|Term | Definition |  
|---|---|
| immutable state | This allows the state to only change when absolutely necessary to make React apps perform as well as possible. https://redux.js.org/faq/immutable-data#what-are-the-benefits-of-immutability|
| time travel in redux | This is a feature of redux dev tools that allows you to see every state that a page has been in. https://medium.com/the-web-tub/time-travel-in-react-redux-apps-using-the-redux-devtools-5e94eba5e7c0|
| action creator | Actions send data from your application to your store, and are the only source of information for the store. An action creator is a function that creates an action. https://redux.js.org/basics/actions|
| reducer | Reducers tell the application how to change state in response to an action. https://redux.js.org/basics/reducers|
| dispatch | This is the name of the function you use to send actions to the store. https://redux.js.org/basics/actions|
