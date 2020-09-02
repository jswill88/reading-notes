# Message Queues
__What does it mean that web sockets are bidirectional? Why is this useful?__  
Bidirectional means that both parties on either side of a network can experience the same thing simultaneously. This is in contrast to HTTP that will either do a request or a response.  
https://medium.com/@nerdplusdog/websocket-simultaneous-bi-directional-client-server-communication-e7948203054b  
__Does socket.io use HTTP? Why?__  
Socket.io uses the WebSocket Protocol instead of HTTP because it allows for real time data transfer.  
https://en.wikipedia.org/wiki/Socket.IO  
__What happens when a client emits an event?__  
The server will listen for that event and react to it, and it will alert other clients if it is supposed to.  
https://nodesource.com/blog/understanding-socketio/  
__What happens when a server emits an event?__  
All of the sockets/clients listening to the server will react to the event.  
https://dev.to/mohamedashrafothman/an-introduction-to-socket-io-3ncb  
__What happens if a client “misses” an event?__   
This could seriously interupt the flow of an application where events rely on one another.  
__How can we mitigate this?__  
We need to use great error handling to catch there problems when they occur and to minimize the problems associated with a missed connection.  

|Term | Definition |  
|---|---|
| Web Socket | The communication protocol that allows a client and a server to connect over a TCP protocol. The Web Socket remains open to allow real time data transfer. https://www.educba.com/websocket-vs-socket-io/ |
| Socket.io | Socket.io broadcasts mulitple sockets at a time, and it works on all platforms. It also allows real time data transfer, and there are many advantages to Socket.io https://www.educba.com/websocket-vs-socket-io/|
| Client | This is what accesses a server to get information. The client is the one asking for information or data, and the server is providing it. https://techterms.com/definition/client|
| Server | A server provides functionality, data, and information to clients. A single server can serve mulitple clients. https://en.wikipedia.org/wiki/Server_(computing)#:~:text=In%20computing%2C%20a%20server%20is,called%20the%20client%E2%80%93server%20model.|
