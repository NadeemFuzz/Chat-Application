# Chat-Application
Distributed Multithreaded client server chat application 


----------------------------------------------------------------


Objective: This assignment has been designed for students to apply appropriate concurrent & network program design methods in designing and implementing a distributed concurrent program. Distributed multithreaded client server chat application You are required to write a windows based C# program to implement a distributed multithreaded client server chat application.

Overview The chat application consists of two main components namely client and the server. The chat server should be a multithreaded server where it can accept multiple client request in parallel mode. New threads needs to be spawn to handle incoming client request.The server should be able to handle all the connected chat client in parallel. There will be no client to client communication. The server is responsible to get all the client messages and communicate those messages back to all the clients. Server can be a console application where it display the connected client information and the status of the chat room. Following is a sample GUI of the server component.

There can be up to 30 clients registered in the chat room. Multiple clients should be able to send multiple messages at the same time. Every client will have an area where they can view the latest 32 messages send by all the clients. Locking mechanisms need to be used to protect access to the public chat area. This also requires the use of conditional wait and notify to block asynchronous access when a new message needs to be displayed in the public chat area. The messages should appear the order they have sent by the clients. The public area displaying the recent messages need to be read-only. In the client window should have a text field and a “send” button. The client should be able to enter the new message in to the text field and use the button to send the message. As soon after sending every client should immediately see the new message in their own display area. Following is a sample GUI of the client Window.

By clicking of a name on the right panel in the chat window the user can start a private chat with that particular user. Clients should be able to perform multiple private chats with different clients. Following is a sample GUI of a private chat window.
