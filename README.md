
# Cloud Chat

http://clust-publi-1m9vd7hqg31bh-587628207.us-east-1.elb.amazonaws.com/

A simple chat client to experiment with AWS Fargate and Socket.io.

## How to use

```
$ cd socket.io
$ npm install
$ cd examples/chat
$ npm install
$ npm start
```

And point your browser to `http://localhost:3000`. Optionally, specify
a port by supplying the `PORT` env variable.

## Features

- Multiple users can join a chat room by each entering a unique username
on website load.
- Users can type chat messages to the chat room.
- A notification is sent to all users when a user joins or leaves
the chatroom.
