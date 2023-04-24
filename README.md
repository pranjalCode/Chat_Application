# Chat_Application
A chat application is a software program that enables real-time communication between two users over a network.

A Java socket programming chat application that uses DataInputStream and DataOutputStream to send and receive messages, and Calendar to display the timestamp
of each message, would allow users to communicate with each other in real-time over a network.

To implement this chat application, we would need to create two classes, a client class and a server class, both of which would extend the Thread class. The client
class would be responsible for sending messages to the server, while the server class would be responsible for receiving messages from the client and broadcasting 
them to all connected clients.

In the client class, we would use a Socket object to establish a connection with the server, and then use a DataOutputStream object to send messages to the server. 
To add timestamps to each message, you would use the Calendar class to get the current date and time, and then format it as a string and include it in the message 
before sending it to the server.


Overall, this chat application would allow users to communicate with each other in real-time over a network, with each message including a timestamp that indicates 
when it was sent.
