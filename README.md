# 🌐 Social Media Application (MERN Stack)

A full-stack social media web application built using **MERN (MongoDB, Express.js, React, Node.js)**.  
It allows users to create, edit, and share posts, interact with other users through likes and comments, and manage social connections with follow/unfollow functionality.

---

## 🚀 Features

### 🖥 Pages & Core UI
- **Home** – Displays latest posts from all users.
- **All Posts** – Explore all public posts.
- **Create Post** – Add new text/image posts.
- **Edit Post** – Update your existing posts.
- **Single Post** – View detailed post with comments.
- **User Posts** – View all posts from a specific user.
- **Login Page** – Secure user authentication.
- **Register Page** – Create a new account.

### 🤝 Social Interaction
- **Like/Unlike** posts.
- **Add/Remove Comments**.
- **Follow/Unfollow** other users.
- **View Followers & Following**.

---

## 🛠 Tech Stack

**Frontend**  
- React.js (Functional Components, Hooks)
- React Router DOM
- Axios for API calls
- Tailwind CSS / CSS Modules (responsive UI)

**Backend**  
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- Bcrypt.js for password hashing

**Other Tools**  
- Cloudinary for image uploads (if implemented)
- Nodemailer for notifications (optional)
- Postman for API testing

---


## 🔐 Authentication & Authorization

- **JWT-based authentication** stored in HTTP-only cookies/local storage.
- Protected routes for creating, editing, and deleting posts.
- Role-based checks to ensure only owners can modify their posts.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/yourusername/social-media-app.git
cd social-media-app

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret


