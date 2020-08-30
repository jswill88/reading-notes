# TCP Servers

__Given the examples of front-end events such as button click, window resize, form submit, etc, what are some examples of back-end events?__  
An example would be a user going online or offline, or it can check that an email or message was sent.  
https://www.freecodecamp.org/news/using-events-in-node-js-the-right-way-fc50c060f23b/  

__Why are events sometimes better than asynchronous actions with callbacks?__  
The benefit of events is that they can handle more complex tasks in a readable way, and they can be called many times, whereas a Promise can only be resolved once.  

__What does an EventEmitter instance do?__  
The instance can set an event listener that will trigger a function when a certain event occurs. you can attach in to the triggering function and to function that will be called.  
https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming  
__When is a program’s call stack, event queue, and event loop active?__  The event loop runs continuously. The event queue is where event handler functions wait to execute. The call stack is where functions wait to execute.  
https://medium.com/@Rahulx1/understanding-event-loop-call-stack-event-job-queue-in-javascript-63dcd2c71ecd  

|Term | Definition |  
|---|---|
| Observer Pattern | An object, called the subject, will have observers. When the state changes, the subject will immediately notify the objects. https://en.wikipedia.org/wiki/Observer_pattern#:~:text=The%20observer%20pattern%20is%20a,calling%20one%20of%20their%20methods. |
| Listener | Something that listens for an event that will trigger a function. https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming|
| Event Handler | The callback function that will run when an event triggers it. |
| Event Driven Programming | Programming where when an event happens, the next function is called. It makes use of callback functions with an event handler, and a main loop that listens for event triggers. https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming|
| Event Loop | When Node.js starts, it kicks off the event loop. There is a queue of phases that the loop goes through one at a time, and it will go back to the top when it is done with all of the phases. https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/|
| Event Queue | A queue where each "node" contains an event, and the application will run through the events as part of the event loop. It is a way to acheive asynchronous programming. https://wiki.c2.com/?EventQueue#:~:text=A%20queue%20that%20contain%20events,an%20EventQueue%20for%20later%20processing.|
| Call Stack | The call stack is where functions are placed before they are called. When another function is called within a function, the called function goes to the top of the stack. |
| Emit/Raise/Trigger |Emitters are the objects that trigger events. Raising describes when the event is emitted. https://www.digitalocean.com/community/tutorials/using-event-emitters-in-node-js |
| Subscribe | This is how you listen for an event to happen. You subscribe to an event that will trigger the callback function. https://www.tutorialsteacher.com/nodejs/nodejs-eventemitter|
| database | A structured and organized collection of data that is stored and accessed by a computer system. https://en.wikipedia.org/wiki/Database|