# Custom Hooks 

__What does a component's lifecycle refer to?__  
__Why do you sometimes need to “wrap” functions in `useCallback` when called from within `useEffect`?__  
__Why are functional components preferred over class components?__  
__What is wrong with the following code?__  
```js
import React, {useState, useEffect} from 'react';

function MyComponent(props) {
  const [count, setCount] = useState(0);

  function changeCount(e) {
    setCount(e.target.value);
  }

  let renderedItems = []

  for (let i = 0; i < count; i++) {
    useEffect( () => {
      console.log('component mount/update');
    }, [count]);

    renderedItems.push(<div key={i}>Item</div>);
  }

  return (<div>
     <input type='number' value={count} onChange={changeCount}/>
      {renderedItems}
    </div>);
}
```
|Term | Definition |  
|---|---|
| State Hook | |
| effect hook | |
| reducer hook | |
