# Real-Time Chat Application (WhatsApp Clone)

A full-stack, real-time messaging application inspired by WhatsApp. Built with the MERN stack and Socket.io, this application allows users to engage in secure one-on-one conversations, create group chats, and toggle dark mode for a better user experience.

## 🚀 Features

* **Real-Time Communication:** Instant messaging powered by **Socket.io** for seamless, lag-free chatting.
* **Secure Authentication:** User signup, login, and logout securely managed using **JWT** (JSON Web Tokens) and **bcrypt** for password hashing.
* **One-on-One & Group Chats:** Create private chats with other users or create groups to broadcast messages to multiple people.
* **Dark Mode:** Built-in dark and light theme toggling for an optimized viewing experience.
* **Typing Indicators:** See when the other person is typing in real-time.
* **Responsive UI:** A clean, mobile-friendly interface designed for cross-device compatibility.

## 🛠️ Tech Stack

* **Frontend:** React.js
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Real-Time WebSockets:** Socket.io
* **Authentication:** JWT, bcrypt

## 📁 Project Structure

    chat-app/
    ├── client/               # React frontend application
    │   ├── public/
    │   ├── src/
    │   │   ├── components/   # Reusable UI components (chat box, sidebar, etc.)
    │   │   ├── pages/        # Main application pages (Login, Chat, etc.)
    │   │   └── App.js
    │   └── package.json
    └── server/               # Node.js backend application
        ├── config/           # Database connection configuration
        ├── controllers/      # Route logic and database operations
        ├── models/           # Mongoose schemas (User, Message, Chat)
        ├── routes/           # API endpoints
        ├── server.js         # Main server entry point
        └── package.json

## ⚙️ Setup and Installation

Follow these steps to set up and run the project locally on your machine.

### 1. Clone the repository
    git clone https://github.com/rrtiwari/your-repo-name.git

### 2. Backend Setup
Navigate to the server folder, install dependencies, and create your environment variables.

    cd server
    npm install

Create a `.env` file inside the `server` folder and add:

    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key

Start the backend server:

    npm start

### 3. Frontend Setup
Open a new terminal window, navigate to the client folder, and start the React app.

    cd client
    npm install

Start the frontend development server:

    npm start

*The frontend will typically run on http://localhost:3000 and the backend on http://localhost:5000.*

## 👤 Author

**Rahul Tiwari**
