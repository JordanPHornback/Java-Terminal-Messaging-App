# Java-Terminal-Messaging-App

This is a java messaging app run through terminal.

Start up the Server.java file (currently set to run on localhost port 8000), then start up the Client.java file (as many as you want, also set to 
localhost port 8000)

Each client will be prompted to enter their username for the group chat.

Clients already in the chat will be notified of each new client that joins.

Messages will be announced to all clients (not the one who sent it) prefaced with the sender's username.

Currently there is a bug where the Server will crash if a client disconnects, working on fixing that now.
