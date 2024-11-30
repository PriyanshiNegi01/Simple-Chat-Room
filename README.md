# Simple Chat Room using Python and TCP Protocol

A chatroom is a minimal chatting application. The Network paradigm involves thinking of computing in terms of a client and a server.
Network programming uses a particular type of network communication known as sockets. A socket is a software abstraction for an
input or output medium of communication.

A socket is one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to. An endpoint is a combination of an IP address and a port number.

## Functions Used

### Server Side:
- socket()
- bind()
- listen()
- accept()
- send()
- recv()
- close()

### Client Side:
- socket()
- gethostbyname()
- connect()
- send()
- recv()
- close()

## Algorithm

### TCP Server:
1. Create a socket
2. Bind it to the operating system.
3. Listen over it.
4. Accept connections.
5. Receive data from client and  send it back to client.
6. Close the socket.

### TCP Client:
1. Create a socket.
2. Connect to the server using connect().
3. Send data to server and receive data from the server.
4. Close the socket.
