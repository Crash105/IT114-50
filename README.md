# Chatroom Application

## Instructions on how to launch and use the application

### Setup
1. Clone the Github repo
2. Go to the project root
3. Type the following commands in separate terminals:

```bash
javac Project/server/Server.java
java Project.server.Server
```

```bash
javac Project/client/ClientUI.java
java Project.client.ClientUI
```

**Note:** The more times you execute the ClientUI code, the more clients you can have in your chatroom application.

## Commands

### Basic Commands
- **flip**: Gives the output of randomly throwing Heads or Tails
- **roll [number]**: For example, when you type `roll 20`, it will generate a random number between 1 and 20

### Private Messaging
- **whisper**: To send a private message to a user, use the format: `@username@message`
  - Example: `@Dan@Hello, good to see you`

### User Management
- **mute user**: To mute a user (you won't see their messages), type `/mute username`
- **unmute user**: To unmute a previously muted user, type `/unmute username`

### Room Management
- **createroom**: To create a chatroom, type `/createroom [number]`
  - The number is an identifier for the chatroom
  - When you create a room, you automatically join it
  - Only people in the same room can send messages to each other
- **joinroom**: To join a chatroom, type `/joinroom [number]`
  - The number is the identifier of the chatroom you want to join

## Message Formatting

To format messages, put the formatting symbols around the text you want to format:

| Format | Symbol | Description |
|--------|--------|-------------|
| Red text | `#r#text#r#` | Turns the color of message red |
| Blue text | `#b#text#b#` | Turns the color of message blue |
| Green text | `#g#text#g#` | Turns the color of message green |
| Italics | `--text--` | Italicizes the message |
| Underline | `__text__` | Underlines the message|
| Bold | `**text**` | Bolds the message |
