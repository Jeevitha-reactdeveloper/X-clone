#  X-Clone – Full Stack Social Media Application

X-Clone is a full-stack social media web application inspired by X (Twitter).  
Users can create posts, like, comment, follow other users, edit their own profiles, and receive notifications.

Built using the MERN stack with secure authentication and cloud-based image storage.

---

## 🔗 Live Demo

Frontend: https://x-clone-frontend-chi.vercel.app/ 
Backend API: https://x-clone-snowy-one.vercel.app/

---

## 📌 Features

### 👤 Authentication
- User Signup & Login
- Secure password hashing before storing in database
- JWT-based authentication
- Protected routes

### 📝 Posts
- Create new posts
- View list of posts from other users
- Like & Unlike posts
- Comment on posts

### 🤝 Social Features
- Follow / Unfollow users
- View other user profiles
- Edit own profile information
- Profile image upload

### 🔔 Notifications
- Notification page for user interactions

### ☁️ Image Upload
- Cloudinary integration for profile images

### ⚡ State Management
- TanStack Query for API data fetching & cache management

---

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- TanStack Query
- Axios
- React Router

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Password Hashing (bcrypt)
- Cloudinary (Image Storage)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

git clone https 

cd x-clone

### 2️⃣ Install dependencies

Frontend:
cd frontend
npm install
npm run dev

Backend:
cd backend
npm install
npm run server

---

## 🔐 Environment Variables

Create a `.env` file in backend:

PORT = 
MONGO_URI =
JWT_SECRET=
NODE_ENV=
CLOUDINARY_API_KEY =
CLOUDINARY_API_SECRET =
CLOUDINARY_CLOUD_NAME =
CLIENT_URL=

---

## 🧠 What I Learned

- Implementing secure authentication with JWT
- Hashing passwords before storing in MongoDB
- Managing server state using TanStack Query
- Handling follow/unfollow logic
- Uploading and managing images using Cloudinary
- Debugging authentication and logout issues
- Deploying full-stack applications on Vercel

---

## 🚧 Challenges Faced

- Managing user state after login/logout
- Handling cache invalidation in TanStack Query
- Securing protected routes
- Handling CORS in production environment

---

## 📸 Screenshots

(Add screenshots in ./screenshots folder)

---

## 👩‍💻 Author

Jeevitha Vijayanand  
LinkedIn: https://www.linkedin.com/in/jeevitha-frontenddeveloper/
