# Real-Time Chat Application
This is a real-time chat application built using Node.js, Express.js, and Socket.IO. It allows multiple users to join chat rooms and communicate with each other in real-time.

## Installation and Setup
Clone the repository

> git clone <repository-url>
  
Install the necessary dependencies:
cd real-time-chat-application
npm install
  
Start the server:

npm start
Open your web browser and visit http://localhost:3000 to access the chat application.

## Usage
Enter a username and choose a chat room to join.

Start sending messages and communicate with other users in the chat room.

## Features
Real-time communication using Socket.IO for instant message updates.
  
Server-side logic to manage chat rooms, user connections, and message broadcasting.
  
Socket.IO events implemented on the server-side:
connection: Handles a new user connection.
join: Adds a user to a specific chat room.
message: Broadcasts a message to all users in a chat room.
disconnect: Handles user disconnections and cleans up user data.
Socket.IO event listeners implemented on the client-side to update the user interface in real-time.
Proper error handling for invalid chat room names, user names, and other potential issues.

## Testing
To test the chat application with multiple users:

Open multiple browser instances.
Access the chat application using different usernames and join the same chat room.
Start sending messages and observe real-time updates across all instances.


#### This project also includes an optional feature to send private messages to other users in the chat room. To send a private message, use the following command:
  
@username message
  
Replace username with the recipient's username and message with the content of the private message.
