
# 💸 Personal Finance App

A full-stack personal finance web application built with the MERN stack (MongoDB, Express.js, React, Node.js) and secured using JWT-based authentication.

---

## 🧪 Features

- User registration and login with JWT
- Add, update, delete expenses
- View summary of spending
- Responsive frontend

---

## 📁 Project Structure

```
Personal Finance App/
├── backend/        # Node.js + Express API + MongoDB
│   ├── controllers/
│   ├── database/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── .env
│   ├── index.js
│   └── package.json
├── frontend/       # React application
│   ├── public/
│   ├── src/
│   └── package.json
```

---

## ⚙️ Backend Setup

### Prerequisites
- Node.js installed
- MongoDB URI (local or cloud)

### Steps

```bash
cd backend
npm install
```

Create a `.env` file in the `backend/` directory and add:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

To start the backend server:

```bash
npm run dev
```

---

## 🌐 Frontend Setup

### Prerequisites
- Node.js installed

### Steps

```bash
cd frontend
npm install
npm run dev
```

This will run the frontend on `http://localhost:3000`.

---



