# Flask Chat Application

This is a simple chat application built with Flask and Flask-SocketIO.

## Description

The Flask Chat Application allows users to join chat rooms and communicate with each other in real-time. Users can create new rooms or join existing ones by entering a room code.

## Features

- Create new chat rooms with unique codes
- Join existing chat rooms
- Real-time messaging using Flask-SocketIO
- Display of chat room messages
- User join/leave notifications

## Prerequisites

Make sure you have the following software installed on your machine:

- Python 3
- pip package manager

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/Chetan7595/flask-chat-app.git
   ```

## Libraries Used

The following libraries were used in this project:

- [Flask](https://flask.palletsprojects.com/): A web framework for building the application.
- [Flask-SocketIO](https://flask-socketio.readthedocs.io/): Enables real-time communication between the server and clients.
- Random: Generates random codes for creating unique chat rooms.
- String: Provides a set of characters for generating unique codes.

## Usage

1. Start the Flask Application:

  ```shell
  python app.py
  ```
2. Open your web browser and visit http://localhost:5000.
3. Enter a name and choose whether to create a new room or join an existing one.
4. Start chatting with other users in the room.
