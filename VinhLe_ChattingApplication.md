# VinhLe_ChattingAplication
Chatting_app

Project Abstract
It is a console application launched from the command line as well as APIs interface. The server and clients can run on different computers in the same network. Working on Java language

Project Relevance:  There are 3 things linked this lab to the goal of this class. The first goal is the optimization and profiling of the code. Second, we might be able to use what we've learned in class to create a UML diagram that defines how to access all classes. Third, you will need a user-friendly interface.  Lastly, this lab needs to use a database to store all the information of each user on the main server.

Concepts design:
As for contributing to this app, the plan was to come up with simple chat apps and turn them into a community of users designed and implemented for APIs/chat apps. People can chat with other users as private chat, public chat. They can do file sharing. The system will be user-friendly, such as a simple graphical user interface for chatting, sharing files, storing messages. Users can report bugs and admins will react immediately and deal with them quickly


Building
The program has 3 main parts. First is the client, the second is the server, and the last one is the admin. The server application is run as it is required to accept the connection request from the clients(sign up/ sign in). The server will be assigned with the port to receive requests from the clients. The client application is run and a local port number bound by a socket will be assigned along with sending connection requests to the server. A connection will be established between server and client. The text message can be typed in the text field and sent by pressing the send button next to it. The message will be encoded and decoded by the other part using a read message. Admin only has the right to fix bugs, update more features for the application. They don’t have any right to use clients' information for their own benefit.


![diagram](https://user-images.githubusercontent.com/77693627/134155101-aa633d01-6d7d-47ea-9cdc-cf8fbde1c898.PNG)
