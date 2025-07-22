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