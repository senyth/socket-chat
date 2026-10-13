# SocketChat

A real-time chat application with a Material Design-inspired flat layout, built without any UI component libraries. Both the front-end and back-end are written from scratch.

## Tech Stack

- **Angular** – front-end
- **Node.js** – back-end
- **MongoDB** – database
- **Socket** – real-time messaging

## Features

- **Protected chat page** – users who are not logged in are redirected to the login page when they try to access the chat.
- **Automatic registration** – if the username doesn't exist in the database, the user is registered automatically. If it exists, the user is logged in when the password is correct. Otherwise, an error message is displayed.
- **Messenger-style messages** – your own username is not shown on messages you send.
- **Typing indicator** – a typing animation is shown when another user is typing.
- **Auto-scroll** – the chat automatically scrolls down to display the latest message.

## Getting Started

### 1. Start the back-end

```bash
cd chat-app-backend
npm install
npm start
```

### 2. Start the front-end

```bash
cd chat-app-frontend
npm install
ng serve
```

### 3. Open the app

Open your browser and go to [http://localhost:4200](http://localhost:4200) to start using the application.
