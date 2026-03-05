# Socket.IO Interview Questions

---

## Basic Socket.IO Interview Questions

* What is Socket.IO?
* What problem does Socket.IO solve compared to HTTP?
* What is real-time communication?
* Difference between WebSocket and Socket.IO.
* What is the difference between polling and WebSockets?
* How does Socket.IO establish a connection between client and server?
* How do you install and set up Socket.IO in Node.js?
* What is the purpose of `io.on("connection")`?
* What is a socket in Socket.IO?
* Difference between `io.emit`, `socket.emit`, and `socket.broadcast.emit`.
* What is the difference between client-side and server-side Socket.IO?
* How do you send data from client to server using Socket.IO?
* How do you disconnect a socket manually?
* What is acknowledgement (callback) in Socket.IO events?
* How does Socket.IO handle reconnection automatically?

---

## Intermediate Socket.IO Interview Questions

* What are rooms in Socket.IO?
* What are namespaces in Socket.IO?
* What is the difference between rooms and namespaces?
* How do you join a room in Socket.IO?
* How do you leave a room in Socket.IO?
* How do you emit events to a specific room?
* How can you send private messages between two users?
* How does Socket.IO handle multiple clients simultaneously?
* What happens when a client refreshes the page?
* How do you store user identity with a socket connection?
* How can you broadcast messages to all users except the sender?
* What is middleware in Socket.IO?
* How do you authenticate users in Socket.IO?
* What is the difference between `socket.id` and `userId`?
* How do you handle connection errors in Socket.IO?
* What is the ping/pong mechanism in Socket.IO?

---

## Advanced Socket.IO Interview Questions

* How does Socket.IO work internally with WebSocket and HTTP fallback?
* What is the Engine.IO layer in Socket.IO?
* How does Socket.IO manage transport upgrades (polling to websocket)?
* What are scaling issues with Socket.IO?
* Why does Socket.IO not scale well with multiple servers by default?
* How do you scale Socket.IO using Redis Adapter?
* What is sticky session and why is it required for Socket.IO?
* How do you handle millions of concurrent socket connections?
* What happens if a server crashes while sockets are connected?
* How do you implement message delivery guarantees?
* How do you prevent memory leaks in Socket.IO servers?
* How do you handle backpressure in real-time messaging systems?
* How do you rate limit events from a socket?

---

## System Design / Real-World Questions

* Design a real-time chat application using Socket.IO.
* How would you build WhatsApp-like chat using Socket.IO?
* How would you implement typing indicators in chat apps?
* How would you implement online/offline presence?
* How would you implement read receipts?
* How would you store chat messages reliably?
* How would you handle message ordering in distributed systems?
* How would you build real-time notifications for millions of users?
* How do you scale Socket.IO using Redis, Kafka, and load balancers?
* How would you design live collaborative editing (like Google Docs)?
* How would you implement real-time game servers?
* How would you prevent socket event abuse or spam?

---

## Practical Coding Questions

* Write a Socket.IO chat server in Node.js.
* Implement private messaging using rooms.
* Implement user authentication before socket connection.
* Implement online users tracking.
* Implement broadcast messaging except sender.
* Implement auto reconnect logic.

---

## Tricky Interview Questions

* Why choose Socket.IO over pure WebSocket?
* When should you NOT use Socket.IO?
* How do you debug Socket.IO connection issues?
* What is the difference between WebSocket server and Socket.IO server?
* How does Socket.IO behave behind Nginx or load balancers?
