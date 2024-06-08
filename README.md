# Chat Room

A chat room application built using Python threading and sockets, enabling multiple users to communicate over a local network.

## Features

- Multiple users can connect to the chat room.
- Messages are broadcast to all connected users.
- Simple command-line interface.

## Requirements

- Python 3.x

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Dhruv-2905/Chat_Room.git
    cd chat-room
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Start the server:
    ```bash
    python server.py
    ```

2. Start the client:
    ```bash
    python client.py
    ```

3. Enter your username and start chatting!

## Project Structure

chat-room/
│
├── server.py # Server-side script
├── client.py # Client-side script
├── README.md # Project documentation
├── requirements.txt # List of dependencies
└── LICENSE # License file (optional)

## Server Code Overview (`server.py`)

The server script creates a socket and binds it to the specified host and port. It listens for incoming connections and starts a new thread for each connected client.

## Client Code Overview (`client.py`)

The client script connects to the server and allows the user to send and receive messages. It uses threading to handle input and output simultaneously.

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request


## Acknowledgments

- [Python](https://www.python.org/) - Programming language
- [Socket Programming](https://docs.python.org/3/library/socket.html) - Python socket library
- [Threading](https://docs.python.org/3/library/threading.html) - Python threading library

