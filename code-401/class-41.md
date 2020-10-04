# React Native

__Compare and Contrast Redux Toolkit with Redux "Ducks"__  
Ducks seems to be a way to modularize your redux code and make it easier to scale and to understand. Redux toolkit is a way to set up your Redux app with certain functions, and it makes it faster to get your app going quickly.  
https://www.freecodecamp.org/news/scaling-your-redux-app-with-ducks-6115955638be/  
https://redux-toolkit.js.org/introduction/quick-start    
__What is the principle advantage of Redux Toolkit?__  
This is the way Redux recommends that you set up a Redux app. It includes a bunch of useful APIs, and it helps simplify Redux code.  
https://redux-toolkit.js.org/introduction/quick-start#purpose  


|Term | Definition |  
|---|---|
| redux toolkit slices | There is a redux toolkit function called `createSlice()` that takes in an initial state, an object of reducer functions, and a 'slice name', and it generates action creators and action types corresponding to the reducers and state. https://redux-toolkit.js.org/api/createSlice|
| namespace | You can create namespaces for action creators in Redux. This allows multiple instances of components to co-exist with independent space. https://www.npmjs.com/package/redux-namespaces|
