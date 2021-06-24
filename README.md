# Realtime_GroupChat_App_NodeJS_SocketIO
WhatsApp Clone - Realtime multiclient chat application using NodeJS and SocketIO

Socket.IO is a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers. It has two parts: a client-side library that runs in the browser, and a server-side library for Node.js. Both components have a nearly identical API.
My realtime group chat app is mainly based on 3 major events:
### Event-1:
If any new user joins, let other users connected to the server know. Here server listens to the incoming events from the client side.
### Event-2:
If someone sends a message, broadcast it to other people in the group.
### Event-3:
If any user leaves the chat, let other chat members know. 
