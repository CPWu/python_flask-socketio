# python_flask-socketio

Sockets vs WebSockets vs SocketIO vs Flask SocketIO

A socket is one endpoint of a two-way communication link between two programs running on the network. This is a very low-level thing, everything else is implemented on top of TCP sockets.

WebSocket is a standard communication protocol for the web. It allows for a full-duplex communication channel to be established between a client and a server.

Socket.IO is a communication protocol that builds on top of HTTP and WebSocket, providing extra features such as automatic reconnection, event-based notifications, etc.

Flask-SocketIO is an implementation of the Socket.IO server-side protocol as a Flask extension.