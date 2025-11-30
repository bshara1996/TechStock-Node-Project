# 📦 TechStock - Inventory Management System

A full-stack inventory management system built with React and Node.js, designed for efficient product tracking and management.

## ✨ Features

- **User Authentication** - Secure login system with session management
- **Product Management** - Add, edit, delete, and track inventory items
- **Image Upload** - Support for product images with Multer
- **Real-time Updates** - Dynamic inventory tracking
- **Responsive Design** - Modern UI built with React and Material-UI

## 🛠️ Tech Stack

### Frontend
- **React 18** - UI library
- **Vite** - Build tool and dev server
- **Material-UI** - Component library
- **React Router** - Client-side routing
- **Axios** - HTTP client

### Backend
- **Node.js** - Runtime environment
- **Express** - Web framework
- **MySQL** - Database
- **bcrypt** - Password hashing
- **express-session** - Session management
- **Multer** - File upload handling

## 📋 Prerequisites

- Node.js (v14 or higher)
- MySQL Server
- npm or yarn

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd TechStock-Node-Project-main
   ```

2. **Set up the database**
   ```bash
   mysql -u root -p < techStock.sql
   ```

3. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

4. **Install frontend dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

## 🚀 Running the Application

### Start the Backend Server
```bash
cd backend
npm start
```
The backend will run on `http://localhost:3000`

### Start the Frontend
```bash
cd frontend
npm start
```
The frontend will run on `http://localhost:5173`

> **Note:** The Vite dev server automatically proxies API requests to the backend.

## 👤 Test Users

| Email | Password |
|-------|----------|
| bshara.karkaby@gmail.com | bshara1 |
| monermahkouly@gmail.com | moner123 |
| evgenia.handessaim@gmail.com | evg2025 |

## 📁 Project Structure

```
TechStock-Node-Project-main/
├── backend/
│   ├── app.js              # Express server entry point
│   ├── dbSingleton.js      # Database connection
│   ├── auth/               # Authentication logic
│   ├── routes/             # API routes
│   └── uploads/            # Uploaded product images
├── frontend/
│   ├── src/                # React source files
│   ├── public/             # Static assets
│   └── vite.config.js      # Vite configuration
├── techStock.sql           # Database schema
├── ERD-Complete.png        # Complete database diagram
└── ERD-Used-In-This-Project.png  # Project-specific ERD
```

## 📊 Database Schema

The database schema is included in `techStock.sql`. View the ERD diagrams for a visual representation of the database structure.

## 🔐 Security

- Passwords are hashed using bcrypt
- Session-based authentication
- CORS enabled for frontend-backend communication

## 👥 Students

- Bshara Karkaby [49-2]
- Moner Makhouly [49-2]

---

**Happy coding!** 💻✨
