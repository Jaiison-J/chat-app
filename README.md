# Simple Python Chat Application

This is a basic command-line chat application built with Python sockets and threading.  
It allows multiple clients to connect to a server and chat in real time.

## Features

- Multi-client support (each client in a separate terminal)
- Real-time message broadcasting
- Nickname support

## How It Works

- The *server* listens for incoming connections.
- Each *client* connects, chooses a nickname, and can send/receive messages.
- All messages are broadcast to every connected client.

## Getting Started

### 1. Clone the repository

```sh
git clone https://github.com/yourusername/chat-app.git
cd chat-app

2. Run the server
Open a terminal and run:

python server.py

3. Run the client(s)
Open one or more terminals and run:

python client.py

Enter a nickname when prompted.

4. Start chatting!
Type messages in any client window and see them appear in all others.

Files
server.py — The chat server
client.py — The chat client

Requirements
Python 3.x (no external libraries needed)

Example

[Terminal 1]
Choose your nickname: Alice
Alice joined the chat!
Bob: Hello everyone!
Alice: Hi Bob!

[Terminal 2]
Choose your nickname: Bob
Bob joined the chat!
Bob: Hello everyone!
Alice: Hi Bob!