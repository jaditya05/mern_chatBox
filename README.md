# 🗣️ Chatterbox: The Ultimate Real-Time Chat Experience

![Chatterbox Mockup](https://raw.githubusercontent.com/jaditya05/mern_chatBox/main/assets/mockup.png)

Chatterbox is a high-performance, real-time messaging platform built for the modern web. Leveraging the power of the **MERN Stack** and **Socket.io**, it provides a seamless, secure, and intuitive way for users to connect instantly.

---

## ✨ Features

### 📡 Real-Time Communication
- **Instant Messaging**: Messages are delivered instantly using WebSockets.
- **Typing Indicators**: See when your friends are typing in real-time.
- **Status Updates**: Know when users are online or offline.

### 🛡️ Security & Authentication
- **Secure Auth**: JWT-based authentication for robust security.
- **Encrypted Passwords**: Industry-standard Bcrypt hashing to protect user data.
- **Protected Routes**: Only authorized users can access chat features.

### 👥 Chat Management
- **One-on-One**: Start a private conversation with any registered user.
- **Group Chats**: Create groups, add/remove members, and manage roles seamlessly.
- **User Search**: Easily find friends by name or email.

### 🎨 Premium UI/UX
- **Chakra UI**: A sleek, accessible, and responsive design system.
- **Glassmorphism**: Modern aesthetic with beautiful gradients and blur effects.
- **Responsive Design**: Works perfectly across desktops, tablets, and mobile devices.

---

## 🛠️ Technology Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React 18, Chakra UI, Axios, Socket.io-client, Framer Motion |
| **Backend** | Node.js, Express.js, Socket.io |
| **Database** | MongoDB with Mongoose ODM |
| **Authentication** | JSON Web Tokens (JWT), Bcrypt.js |

---

## 🚀 Getting Started

### Prerequisites
- **Node.js** (v16.x or higher)
- **npm** or **yarn**
- **MongoDB** (Local or Atlas)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/mern_chatBox.git
   cd chatterbox
   ```

2. **Backend Setup**
   ```bash
   # Navigate to the root directory
   npm install
   ```

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   ```

### ⚙️ Environment Variables
Create a `.env` file in the **root directory** and add the following:

```env
PORT = 5000
MONGO_URI = your_mongodb_connection_string
JWT_SECRET = your_super_secret_key
```

### 🏃 Running the Application

1. **Start the Backend** (From the root directory)
   ```bash
   npm start
   ```

2. **Start the Frontend** (In a new terminal)
   ```bash
   cd frontend
   npm start
   ```

The app will be running at `http://localhost:3000` and the API at `http://localhost:5000`.

---

## 📂 Project Structure

```text
├── backend/
│   ├── config/         # Database configuration
│   ├── controllers/    # Business logic
│   ├── middleware/     # Auth & Error handlers
│   ├── models/         # Mongoose schemas
│   ├── routes/         # API endpoints
│   └── server.js       # Entry point & Socket.io setup
├── frontend/
│   ├── public/         # Static assets
│   └── src/
│       ├── components/ # Reusable UI components
│       ├── Context/    # Global state management
│       ├── Pages/      # Main application views
│       └── App.js      # Routing setup
└── package.json        # Main dependencies & scripts
```

---

## 🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License
Distributed under the **ISC License**. See `LICENSE` for more information.

## 📬 Contact
**Your Name** - [jonnalagadda.aditya5@gmail.com ](mailto:jonnalagadda.aditya5@gmail.com)

Project Link: [https://github.com/jaditya05/mern_chatBox](https://github.com/jaditya05/mern_chatBox)

---
*Created with ❤️ by Aditya*
