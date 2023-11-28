![status](https://badgen.net/static/status/planned/grey/)

# Elixir chat app

This repository contains code of a learning project called: "Elixir chat app".

It's purpose is to build a real-time chat application using Elixir and Phoenix.

## Idea

The project involves creating a chat application using Elixir and the Phoenix Framework, a web framework built with Elixir. The application will have several key features. First, it will implement user authentication, allowing users to sign up, log in, and log out. Second, it will use Phoenix Channels, which utilize WebSockets, to implement real-time messaging, enabling users to send and receive messages instantly. Third, it will allow users to create and join different chat rooms, providing a platform for group discussions. Lastly, it will store message history in a database using Ecto, a database wrapper and query generator for Elixir.

## Learning

- Elixir
- Phoenix
- Ecto
- WebSockets
- Message history
- Database performance

## Requirements

- A user must be able to sign up to create an account.
- A user must be able to log in to their account.
- A user must be log out of their account.
- A user must be able to send messages to another use in real-time.
- A user must be able to create chat rooms.
- A user must be able to join a chat room by using a given UUID.
- A user must be able to leave a chat room.
- A chat room must be deleted whenever everyone has left.
- Old messages must be shown again when opening a chat.
- Only a certain amount of old messages must be retrieved at a time to improve database performance.
