# Sockets.io

__What is the benefit of transforming data into packets?__  
This is an efficient way of transfering data over networks and it limits latency.  
https://en.wikipedia.org/wiki/Packet_switching#:~:text=Packet%20switching%20is%20used%20to,to%20increase%20robustness%20of%20communication.  
__UDP is often refereed to as a connectionless protocol. Why is this?__  
This is because with UPD no connection needs to be established between the origin and destination before tranferring data.  
https://www.sciencedirect.com/topics/computer-science/connectionless-protocol#:~:text=DNS%2C%20TFTP%2C%20and%20many%20other,the%20payload%20is%20not%20corrupted.  
__Can a socket server application have multiple socket connections?__  
Yes, a socket server can have more than one socket connection. We did this during our lab.  
__Can a socket connection application be connected to multiple socket servers?__  
I do not believe so. Each socket is bound to a single port.  
https://docs.oracle.com/javase/tutorial/networking/sockets/definition.html#:~:text=Definition%3A,address%20and%20a%20port%20number.  
__Can an application be both a socket server and a socket connection?__   
It seems that a socket is mostly used to connect to a socket server, and not to be a server itself. However, I don't see why you could not have both in the same application.  
https://nodejs.org/api/net.html#net_class_net_socket  



|Term | Definition |  
|---|---|
| OSI Model | OSI stands for Open System Interconnection. It is a conceptual framework for understanding the networking process. The seven layers of OSI are Physical, Data Link, Network, Transport, Session, Presentation, and Application. https://www.webopedia.com/quick_ref/OSI_Layers.asp |
| TCP Model | This is a more concise version of the OSI Model, and it consists of four layers: Application, Transport, Internet, and Network. https://www.geeksforgeeks.org/tcp-ip-model/|
|TCP | This stands for Transmission Control Protocol. In this, the server must be listening for connections from clients.  https://en.wikipedia.org/wiki/Transmission_Control_Protocol|
|UDP | This stands for User Datagram Protocol. Unlike TCP, there is no need to establish a connection before transfering data.  https://www.geeksforgeeks.org/user-datagram-protocol-udp/ |
| Packets | A unit of data that goes from one place to another over a network. https://searchnetworking.techtarget.com/definition/packet#:~:text=A%20packet%20is%20the%20unit,passed%20over%20TCP%2FIP%20networks.|
| Socket | A socket is an endpoint for sending and receiving data. Sometimes this refers to an internet socket, where a socket is identified to other hosts by its socket address. https://en.wikipedia.org/wiki/Network_socket|
