# 📸 Instagram Clone

This is an **Instagram Clone** built with the **MERN stack** (MongoDB, Express, React, and Node.js). This application simulates core Instagram features, including user authentication, posting images, liking, commenting, following, and a real-time feed.

## 🚀 Features

- **User Authentication**: Register, login, and logout securely with JWT-based authentication.
- **Profile Management**: Edit your profile information and view other users' profiles.
- **Post Creation**: Upload images, captions, and hashtags.
- **News Feed**: See posts from users you follow.
- **Like & Comment**: Engage with posts by liking and commenting.
- **Follow System**: Follow/unfollow users to customize your feed.
- **Real-Time Notifications**: Get notified when others like or comment on your posts.
- **Responsive Design**: Optimized for both desktop and mobile views.

## 🛠️ Technology Stack

- **Frontend**: React, Redux, Tailwind CSS (or CSS/SCSS)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose ORM)
- **Authentication**: JSON Web Tokens (JWT)
- **Storage**: Cloudinary for image storage (optional)

## 📂 Project Structure

```plaintext
instagram-clone/
│
├── client/                  # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/      # Reusable components (e.g., Post, Feed, Profile)
│   │   ├── reducers/           # Redux slices and actions
│   │   ├── App.js           # Main application file
│   │   └── index.js         # Entry point for React
│   └── package.json
│
└── server/                  # Node.js backend
    ├── models/              # Mongoose models
    ├── routes/              # API routes
    ├── middleware/          # Auth middleware
    ├── config/              # Config files (e.g., database, JWT)
    └── package.json
```

## 🖥️ Installation & Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/Instagram-Clone.git
   cd Instagram-Clone
   ```

2. **Install Dependencies**

    Install dependencies for both the client and server.

    In the `client` directory:

    ```bash
    cd client
    npm install
    ```

    In the `server` directory:

    ```bash
    cd ../server
    npm install
    ```

3. **Environment Variables**
    Set up environment variables to configure the project for MongoDB and JWT.

    Add the following variables to the keys.js file:

    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. **Start the Application**
    Run both the client and server to start the application.

    In the client directory, run:

    ```bash
    npm start
    In the server directory, run:
    ```

    ```bash
    npm start
    ```

5. **Access the Application**
    Once both servers are running:

    The frontend is accessible at http://localhost:3000,
    The backend API is accessible at http://localhost:5000