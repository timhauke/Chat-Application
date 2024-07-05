# Chat Application

Welcome to the **Chat Application** repository! This project provides a real-time messaging platform, allowing users to communicate with each other instantly. It supports both one-on-one and group chats with a modern and responsive interface.

## Features

- **Real-Time Messaging**: Send and receive messages instantly using WebSockets.
- **User Authentication**: Secure login and registration system.
- **One-on-One Chats**: Private messaging between users.
- **Group Chats**: Create and join group chats for team communication.
- **Message History**: Persistent message history for all conversations.
- **Online Status**: See when your contacts are online.
- **Typing Indicators**: Real-time typing notifications.
- **Read Receipts**: See when your messages have been read.
- **File Sharing**: Share images, videos, and documents within chats.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies

- **Frontend**: HTML5, CSS3, JavaScript, React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-Time Communication**: WebSocket (Socket.io)
- **Authentication**: JSON Web Tokens (JWT)
- **Deployment**: Netlify, Vercel, Heroku

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/chat-application.git
   cd chat-application
   ```

2. **Install frontend dependencies**:
   ```bash
   cd client
   npm install
   ```

3. **Install backend dependencies**:
   ```bash
   cd ../server
   npm install
   ```

4. **Configure the environment variables**:
   - Create a `.env` file in the `server` directory and add your MongoDB URI and JWT secret.
   ```
   MONGO_URI=your_mongo_db_uri
   JWT_SECRET=your_jwt_secret
   ```

5. **Run the backend server**:
   ```bash
   npm start
   ```

6. **Run the frontend application**:
   ```bash
   cd ../client
   npm start
   ```

7. **Access the application**:
   - Navigate to `http://localhost:3000` in your web browser.

## Usage

1. Sign up for a new account or log in if you already have one.
2. Start a one-on-one chat by searching for users.
3. Create and join group chats for team or community communication.
4. Send text messages, share files, and see real-time updates.
5. Enjoy features like typing indicators, read receipts, and online status notifications.

## Project Structure

- `client/`: React.js frontend source code
- `server/`: Node.js backend source code
- `public/`: Public assets and static files
- `models/`: MongoDB models for storing user data and messages
- `routes/`: API routes for the backend

## License

This project is licensed under the MIT License – see the [LICENSE.md](LICENSE.md) file for details.
