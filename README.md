
# IMAGIFY

**IMAGIFY** is a MERN stack web application built with **MongoDB**, **Express**, **React**, and **Node.js**. This app allows users to interact with image-based content, potentially involving uploads, authentication, and more.

---

## 📁 Project Structure

```
IMAGIFY/
├── client/               # React frontend
│   ├── public/
│   ├── src/
│   ├── .env
│   └── package.json
├── server/               # Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── .env
│   └── package.json
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14+)
- MongoDB (Atlas/local)
- npm or yarn

### 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/IMAGIFY.git
cd IMAGIFY
```

2. Install client dependencies:

```bash
cd client
npm install
```

3. Install server dependencies:

```bash
cd ../server
npm install
```

---

## 🔑 Environment Variables

Create `.env` files in both `client/` and `server/` directories.

### Example `client/.env`
```
REACT_APP_API_URL=http://localhost:5000
```

### Example `server/.env`
```
PORT=5000
MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/imagify
JWT_SECRET=your_jwt_secret
```

---

## 🧪 Running the App

### Start the frontend
```bash
cd client
npm start
```

### Start the backend
```bash
cd server
npm run dev
```

---

## 🛠 Tech Stack

- **Frontend:** React, Axios, React Router
- **Backend:** Node.js, Express, MongoDB, Mongoose
- **Authentication:** JWT
- **Styling:** TailwindCSS 

---

## ✨ Features

- User authentication (Login/Register)
- Upload and manage images
- Secure routes using JWT
- RESTful APIs

---


